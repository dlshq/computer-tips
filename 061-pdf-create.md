# How to create PDF from text files

* [PDF file generate](https://github.com/simonhaenisch/md-to-pdf)
npm i -g md-to-pdf
md-to-pdf [options] path/to/file.md
md-to-pdf ./**/*.md

cat file.md | md-to-pdf > path/to/output.pdf

Tip: You can concatenate multiple files using cat file1.md file2.md.