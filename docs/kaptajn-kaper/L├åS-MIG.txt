Kaptajn Kaper i Kattegat – Remastered Edition 2026

Sådan lægges spillet online som app:
1. Upload HELE mappen "kaptajn-kaper" til en webserver med https
   (fx GitHub Pages eller jeres egen server).
2. Åbn adressen på telefonen, fx https://dinserver.dk/kaptajn-kaper/
3. iPhone (Safari): Del-knappen -> "Føj til hjemmeskærm".
   Android (Chrome): menuen -> "Installer app" / "Føj til startskærm".
4. Spillet starter nu fra hjemmeskærmen i fuld skærm uden adresselinje.
   Når det har været åbnet én gang med net, kan det også startes offline.

Filer (skal ligge sammen i samme mappe):
  index.html            spillet
  manifest.json         navn, ikon og fuld skærm
  icon-192.png, icon-512.png, apple-touch-icon.png   app-ikoner
  sw.js                 offline-funktion

Opdatering: erstat index.html med en ny version. Ved større ændringer kan
"kaptajn-kaper-v1" i sw.js ændres til v2, så gamle kopier ryddes.
