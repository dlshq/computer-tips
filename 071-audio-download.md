# Download audio files

* Get the audio files urls from the page

```javascript
items = document.getElementsByTagName('audio')

for (let index = 0; index < items.length; index++) {
    console.log(items[index].src)
}
```

```bash
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-01-thiruvennainallur-pitha-pirai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-02-thiruthuraiyur-malaiyar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-03-thiruadhigai-thammanai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-04-thiruthinainagar-neeruthangiya.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-05-thirukazhumalam-sathalum-pirathalum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-06-thiruvarur-karaiyum-kadalum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-07-thiruvarur-thillaivazh.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-08-thirukolili-neela.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-09-thirunattiyathankudi-poonan-avathor.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-10-thiruvalivalam-oon-angathu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-11-thirupugalur-thammaiye.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-12-thirupanaiyur-maadamaaligai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-13-nanilam-thanniyil.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-14-thiruveezhimalai-nambinarku.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-15-thiruvanjiyam-poruvanar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-16-thirunaraiyursiddicharam-neerum-malarum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-17-thiruarisilkaraiputhur-malaikum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-18-thiruvavaduturai-maraiyavan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-19-thiruvidaimaruthur-kazhuthai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-20-thirunagecharam-pirai-anivazal.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-21-thirukalayanallur-kurumbai-mulai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-22-thiruchottruturai-azhalneer.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-23-thirumazhaipaadi-ponaarmeniyane.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-24-thiruannaika-maraigal.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-25-thirupacheelacharam-vaithanan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-26-thirupaingeeli-karulaviye.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-27-thirupandikodimudi-mattrupattru.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-28-thiruvenjamakoodal-erikum-kathirvel.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-29-thirukarkudi-vidaiyarum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-30-thirupurambayam-angam-oothi.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-31-thirukoodalayatrur-vadivudai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-32-thirumuthukundram-nanchi-idai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-33-thirumuthukundram-nambipathigam.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-34-kovilchidambaram-madiththadum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-35-thirukaruppariyalur-simmanthu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-36-thirupazhamannipadikarai-munnavan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-37-thiruvazhkoliputhur-thalaikazhalan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-38-thirukannatumullur-valvaye.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-39-thiruedirkolpaadi-madhayanai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-40-thiruthuruthivelvikudi-muppathum-illai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-41-thirumudukunram-ponseitha-meni.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-42-thiruvarur-paaruthangiya.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-43-thirunallaru-sempon-meni.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-44-thirukadavurmayanam-maruvar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-45-thirukadavur-podiyar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-46-thiruvalampuram-yenaku-nee.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-47-thiruvenkaadu-padam-kolnagam.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-48-thirunannipalli-aathiyen-aathi.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-49-thiruninriyur-thiruvum-vanmaiyum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-50-thiruninriyur-attravanar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-51-thiruneedur-oorvathu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-52-thirukolakka-puttril-vazhalaravu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-53-thirukurugavur-ithanai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-54-thirukazhipalai-sediyen.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-55-thirunaavalur-govalan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-56-thiruidaiyaaru-mundhaiyur.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-57-thirukazhukundram-kondru-seitha.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-58-thirukachur-muthuvai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-59-thirukachimetralli-nontha.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-60-thiruonakanthanthali-neyumpalum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-61-thirukachianekathangavatham-thennai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-62-thiruvanparthaanpanangatur-vidaiyin.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-63-thirukaalathi-sendadum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-64-thiruparupatham-maanum-maraiyinamum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-65-thiruketharam-vazhalvavathu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-66-thiruvottriyur-pattum-paadi.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-67-thiruvarur-pathimaiyum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-68-thiruvottriyur-azhuku.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-69-thirumullaivayil-thiruvum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-70-thiruvenpakkam-pizhalai-ullane.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-71-thiruvalangadu-muthaa-mudhi.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-72-thirukacchiekambam-aalamthan-unathu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-73-thiruvarur-andiyum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-74-thiruaamathur-kandanan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-75-thirunelvoyilarathurai-kalvaai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-76-thiruvavaduturai-gangaivar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-77-thiruthuruthi-minnuma.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-78-paravaiunmanthali-thoovaiyar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-79-thiruvarur-kurukupaya.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-80-thiruvarur-meela-adimai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-81-thirupungur-anthenallan.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-82-thirunagaikaronam-pathur.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-83-thirumaraikaadu-yalai-palithena.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-84-thirukodikuzhagar-kadithai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-85-thirupoovanam-thiru-udaiyar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-86-thiruparankunram-kothittaiyum-kovalum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-87-thirukeedicharam-nathaar-padai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-88-thirusuzhiyal-oonai-uyir.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-89-thirukannapair-thondar.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-90-thirupunavayil-chitha-nee.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-91-thiruvarur-iraikalodu.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-92-thiruvarur-veezhakalanai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-93-thiruvarur-kattur-kadale.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-94-thiruvaiyaaru-paravum-parisondru.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-95-thiruanjaikalam-mudipathu-kangaiyum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-96-thiruvarur-ponnum-meiporulum.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-97-thirumuruganpoondi-kodukuvenchilai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-98-thiruavinashi-yettran.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-99-thiruanjaikalam-thalaiku-thalaimalai.mp3
curl -O -J https://shaivamfiles.fra1.cdn.digitaloceanspaces.com/gallery/audio/satguru/sundarar-thevaram/tis-sat-sun-thevaram-100-thirukailayam-thanyenai.mp3
```