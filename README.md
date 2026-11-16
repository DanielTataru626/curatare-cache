# Curățare cache

Aplicație Android care golește memoria cache a tuturor aplicațiilor dintr-o singură apăsare și îți spune cât spațiu s-a eliberat. Este gândită să fie ușor de folosit atât cu TalkBack sau Jieshuo, cât și de cei care văd.

**[Descarcă ultima versiune (fișierul CuratareCache.apk)](../../releases/latest)**

*English summary at the end of this page.*

## Ce face

- Golește cache-ul tuturor aplicațiilor (Facebook, YouTube, eMAG, Chrome, WhatsApp, aplicațiile de sistem și toate celelalte).
- La final anunță cât spațiu s-a eliberat, de exemplu: „Gata. Spațiu eliberat: 1,1 GB.”
- Rezultatul este citit automat de TalkBack și Jieshuo, fără să fie nevoie să glisezi până la el.
- Text mare, buton mare, temă deschisă sau întunecată după setarea telefonului.
- Română pe telefoanele setate în română, engleză pe celelalte.

**Nu se șterg:** conturile și autentificările, pozele, videoclipurile, muzica, documentele, mesajele, descărcările offline și setările aplicațiilor.

## Recunoaște singură telefonul

| Telefon | Cum golește |
|---|---|
| **Samsung** | Prin funcția oficială Android, într-o singură fereastră de confirmare. Cere permisiunea „Acces la toate fișierele”. |
| **Celelalte mărci** (Motorola, Google Pixel, Xiaomi, OPPO, vivo, Huawei și altele) | Android nu permite aici golirea dintr-o dată, așa că aplicația folosește serviciul de accesibilitate Curățare cache: intră singură, pe rând, în Setări, la fiecare aplicație, și apasă „Golește memoria cache”. Durează 1–3 minute și se poate opri oricând cu butonul „Oprește” sau cu o tastă de volum. |

Pe Samsung serviciul de accesibilitate este ascuns și nu apare în Setări.

## Cerințe

- Android 11 sau mai nou.

## Confidențialitate

- Fără acces la internet: aplicația nu trimite nimic nicăieri.
- Pe Samsung, o singură permisiune: „Acces la toate fișierele”, cerută de Android pentru golirea cache-ului tuturor aplicațiilor. Aplicația nu citește și nu modifică fișierele tale.
- Pe celelalte telefoane, serviciul de accesibilitate lucrează doar după ce apeși butonul de golire și apasă numai „Stocare” și „Golește memoria cache”. Nu apasă niciodată „Șterge datele” sau „Dezinstalează” și nu citește conținutul tău.
- Fără reclame, fără colectare de date.

## Instalare

Aplicația nu este în Magazin Play, de aceea Android cere câteva confirmări în plus. Este normal.

1. Descarcă `CuratareCache.apk` de la [Releases](../../releases/latest) direct pe telefon.
2. Deschide fișierul. Dacă telefonul spune că nu permite instalarea din această sursă, apasă **Setări**, activează **Permite din această sursă** și revino cu Înapoi.
3. Apasă **Instalează**.
4. Dacă apare avertismentul **Google Play Protect**, nu apăsa „OK”. Apasă **Mai multe detalii**, apoi **Instalează oricum**. Avertismentul apare la orice aplicație din afara Magazinului Play pe care Google nu o vede pe multe telefoane; nu înseamnă că aplicația este periculoasă.
5. Deschide aplicația și urmează secțiunea **Pregătire**:
   - pe Samsung: **Acordă accesul la toate fișierele** și activează comutatorul;
   - pe celelalte telefoane: **Activează serviciul Curățare cache** și activează comutatorul. Dacă Android spune că setarea este restricționată: Setări, Aplicații, Curățare cache, meniul ⋮, **Permite setările restricționate**.
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

- **Samsung:** uses Android's own "clear the cache of all apps" function (needs "All files access").
- **Other brands** (Motorola, Pixel, Xiaomi and others), where Android offers no such function: the Cache Cleaner accessibility service opens Settings for each app in turn and presses only "Clear cache". It never presses anything else. It can be stopped at any time.
- Requires Android 11 or newer. No internet access, no ads, no data collection.
- Install: download `CuratareCache.apk` from [Releases](../../releases/latest), allow installing from that source, and on the Google Play Protect warning choose **More details**, then **Install anyway**.

Built with the help of Claude, an AI assistant made by Anthropic. Provided free, as is, without warranty, under the [MIT License](LICENSE).
