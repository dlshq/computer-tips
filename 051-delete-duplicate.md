# How to delete duplicate files in a set of directories - Windows

* In **Search** - type **powershell**
* Go to the directory where duplicate files might exist in one or more sub folders
* For example: `cd D:\documents`

## Identify the duplicate files

* The below gets a hashcode for each of the files
* Groups the file by hashcode
* It's rare that two hashcodes for two different files same

```powershell
 Get-ChildItem -Recurse | Get-FileHash | Group-Object -Property Hash | Where-Object { $_.Count -gt 1 } | Select-Object -ExpandProperty Group | Select-Object -ExpandProperty Path
```

## Delete the duplicates

* This keeps only one file and removes all other files

```powershell
Get-ChildItem -Recurse | Get-FileHash | Group-Object -Property Hash | Where-Object { $_.Count -gt 1 } | foreach {
    $group = $_.Group | Select-Object -ExpandProperty Path
    $group | Select-Object -Skip 1 | Remove-Item -Force
}
```