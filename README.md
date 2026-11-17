# Curățare cache

Aplicație Android care golește memoria cache a tuturor aplicațiilor dintr-o singură apăsare și îți spune cât spațiu s-a eliberat. Este gândită să fie ușor de folosit atât cu TalkBack sau Jieshuo, cât și de cei care văd.

**[Descarcă ultima versiune (fișierul CuratareCache.apk)](../../releases/latest)**

*English summary at the end of this page.*

## Ce face

- Golește cache-ul tuturor aplicațiilor (Facebook, YouTube, Chrome, WhatsApp, aplicațiile de sistem și toate celelalte).
- La final anunță cât spațiu s-a eliberat, de exemplu: „Gata. Spațiu eliberat: 1,1 GB.”
- Rezultatul este citit automat de TalkBack și Jieshuo, fără să fie nevoie să glisezi până la el.
- Text mare, buton mare, temă deschisă sau întunecată după setarea telefonului.
- Română pe telefoanele setate în română, engleză pe celelalte.

**Nu se șterg:** conturile și autentificările, pozele, videoclipurile, muzica, documentele, mesajele, descărcările offline și setările aplicațiilor.

## Cum golește

Android nu permite aplicațiilor să golească dintr-o dată tot cache-ul celorlalte aplicații. De aceea, Curățare cache folosește serviciul ei de accesibilitate: intră singură, pe rând, în Setări, la fiecare aplicație, și apasă „Golește memoria cache”, exact cum ai face tu de mână. Durează 1–3 minute și se poate opri oricând cu butonul „Oprește” sau cu o tastă de volum.

Metoda este aceeași pe toate telefoanele: Samsung, Motorola, Google Pixel, Xiaomi, OPPO, vivo, Huawei și altele.

## Cerințe

- Android 11 sau mai nou.

## Confidențialitate

- Fără acces la internet: aplicația nu trimite nimic nicăieri.
- Nu cere nicio permisiune.
- Serviciul de accesibilitate lucrează doar după ce apeși butonul de golire și apasă numai „Stocare” și „Golește memoria cache”. Nu apasă niciodată „Șterge datele” sau „Dezinstalează” și nu citește conținutul tău.
- Fără reclame, fără colectare de date.

## Instalare

Aplicația nu este în Magazin Play, de aceea Android cere câteva confirmări în plus. Este normal.

1. Descarcă `CuratareCache.apk` de la [Releases](../../releases/latest) direct pe telefon.
2. Deschide fișierul. Dacă telefonul spune că nu permite instalarea din această sursă, apasă **Setări**, activează **Permite din această sursă** și revino cu Înapoi.
3. Apasă **Instalează** (sau **Actualizează**, dacă ai deja o versiune mai veche).
4. Dacă apare avertismentul **Google Play Protect**, nu apăsa „OK”. Apasă **Mai multe detalii**, apoi **Instalează oricum**. Avertismentul apare la orice aplicație din afara Magazinului Play pe care Google nu o vede pe multe telefoane; nu înseamnă că aplicația este periculoasă.
5. Deschide aplicația și, la secțiunea **Pregătire**, apasă **Activează serviciul Curățare cache**, apoi activează comutatorul (pe Samsung se află la „Aplicații instalate”). Dacă Android spune că setarea este restricționată: în aplicație apasă **Deschide informațiile aplicației**, apoi meniul ⋮ (Mai multe opțiuni), **Permite setările restricționate**, și încearcă din nou. Opțiunea apare în meniu doar după ce ai primit o dată mesajul de blocare.
6. Apasă **Golește cache-ul tuturor aplicațiilor**.

Ghidul complet, cu problemele frecvente, este atașat fiecărei versiuni de la Releases.

## Verificarea fișierului

La fiecare versiune de la Releases este scris codul SHA-256 al fișierului APK. Dacă vrei, îl poți compara cu cel al fișierului descărcat, ca să fii sigur că nu a fost modificat.

## Despre aplicație

Aplicația a fost realizată cu ajutorul lui Claude, un asistent de inteligență artificială dezvoltat de Anthropic. Ideea, cerințele, testarea pe telefon și verificarea cu TalkBack și Jieshuo au fost făcute de autor.

Oferită gratuit, așa cum este, fără garanții, sub [licența MIT](LICENSE).

Probleme sau idei? Scrie la [Issues](../../issues).

---

## English summary

**Cache Cleaner** clears the cache of every app on an Android phone with one tap and then tells you how much space was freed. The result is read automatically by TalkBack and Jieshuo. Accounts, files, messages and app settings are not touched.

- Android does not let an app clear the whole cache of other apps at once, so the Cache Cleaner accessibility service opens Settings for each app in turn and presses only "Clear cache". It never presses anything else and can be stopped at any time. The same method is used on every brand (Samsung, Motorola, Pixel, Xiaomi and others).
- Requires Android 11 or newer. No permissions, no internet access, no ads, no data collection.
- Install: download `CuratareCache.apk` from [Releases](../../releases/latest), allow installing from that source, and on the Google Play Protect warning choose **More details**, then **Install anyway**. Then turn on the Cache Cleaner accessibility service from the app's Setup section. If Android says the setting is restricted, press **Open App info** in the app, then the ⋮ menu, **Allow restricted settings**, and try again.

Built with the help of Claude, an AI assistant made by Anthropic. Provided free, as is, without warranty, under the [MIT License](LICENSE).
