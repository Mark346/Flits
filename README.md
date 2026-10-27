# Flits ⚡ – leren met flashcards

Leer al je schoolvakken met je eigen kaarten: flashcards met omdraai-animatie, meerkeuze, typen, waar of niet waar, husselen, koppelen, memory, snelrace en oefentoetsen met cijfer. Bij Nederlands zit ook begrijpend lezen.

Alles wordt op het apparaat zelf bewaard (in de browser). Er is geen account en er zijn geen kosten.

## Online zetten met GitHub Pages

1. Maak op github.com een nieuwe repository, bijvoorbeeld `flits` (Public).
2. Klik op **Add file → Upload files** en sleep **alle bestanden uit deze map** erin:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` (en deze `README.md`).
3. Klik op **Commit changes**.
4. Ga naar **Settings → Pages**. Kies bij *Source*: **Deploy from a branch**, branch **main**, map **/ (root)**, en klik **Save**.
5. Na een minuutje staat de app op `https://<jouw-gebruikersnaam>.github.io/flits/`.

## Op de iPhone als app zetten

1. Open de link in **Safari**.
2. Tik op de deelknop (vierkantje met pijl) → **Zet op beginscherm**.
3. Flits staat nu als app met eigen icoon op het beginscherm en werkt ook zonder internet.

## Nieuwe versie uploaden

Upload de nieuwe `index.html` over de oude heen. Verhoog in `sw.js` het nummer bij `VERSION` (bijv. `flits-v2`), dan krijgt iedereen zeker de nieuwste versie.

> Let op: de kaarten staan in de browser van het apparaat. Wis je de websitegegevens van Safari, dan zijn je kaarten weg.
