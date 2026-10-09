# Andmete töötlemine MS Excel

Eestikeelne, piltidega e-kursus Exceli kasutamisest uurimistöö andmete analüüsimisel. Kursus põhineb Ülle Raaveli õppematerjalil „Andmete töötlemine (MS Excel)“ (TLÜ Haapsalu kolledž, 2026).

## Kursuse sisu

Kursus koosneb kümnest teemast ja lõpus olevast teadmiste kontrollist. Teemades käsitletakse muu hulgas andmete ettevalmistamist ja Exceli funktsioone, diagramme, PivotTable'i, kirjeldavat statistikat, korrelatsiooni ning T-testi ja hii-ruut testi. Teadmiste kontrollis on 12 küsimust ja läbimiseks on vaja vähemalt 75% õigeid vastuseid.

## Kasutamine

### Ava brauseris

Ava `index.html` veebibrauseris. Põhisisu ja pildid töötavad staatiliste failidena; eraldi ehitust ega paigaldatavaid sõltuvusi pole.

Üksinda brauseris avades töötab kursus ilma õpikeskkonna salvestuseta. Kui kursus avatakse SCORM 1.2 toega õpikeskkonnast, saadetakse õpikeskkonda võimaluse korral kursuse edenemine ning teadmiste kontrolli tulemus.

### Impordi õpikeskkonda

Paki projekti failid ZIP-arhiivi nii, et `imsmanifest.xml` ja `index.html` paiknevad arhiivi juurkaustas ning `images/` on samal tasemel. Laadi ZIP SCORM 1.2 kursusena üles (näiteks Moodle'i SCORM-pakina). Ära paki arhiivi üleslaadimise eel lahti. Õpikeskkonna seadistusvõimalused võivad olenevalt platvormist erineda.

### Avalda GitHub Pagesis

Laadi hoidlasse üles `index.html`, `imsmanifest.xml` ja kogu `images/` kaust. Projekti avaldamisel juurkaustast peab `index.html` olema selle juurkaustas. GitHub Pages võimaldab kursust veebilehena avada, kuid SCORM-i edenemise salvestamiseks on vaja SCORM-i toetavat õpikeskkonda.

## Failid

- `index.html` — kursuse kujundus, teemad, navigeerimine, edenemine, teadmiste kontroll ja SCORM 1.2 ühendus.
- `imsmanifest.xml` — SCORM 1.2 manifest, mille abil õpikeskkond kursuse käivitab.
- `images/` — kursuse teemade juures kasutatavad õppematerjali kuvatõmmised ja joonised.
- `LOE-MIND.txt` — projekti lühikesed kasutus- ja avaldamisjuhised.

## Muutmine

Kursuse tekst ja kujundus asuvad failis `index.html`. Õppetükid on JavaScripti `lessons` loendis ja teadmiste kontrolli küsimused `quiz` loendis. Pildid on HTML-is seotud suhteliste failiteedega, näiteks `images/image1.png`; failinimede muutmisel uuenda ka vastavaid viiteid. Kui lisad või eemaldad pilte, kontrolli, et failinime suurtähed ja väiketähed kattuksid viites kasutatuga.

