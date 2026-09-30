# Akadémia hrdinov

Učebná appka pre jedno dieťa: rozvrh, príprava na písomky, kartičky, misie a ateliér.
Beží celá v prehliadači, bez servera. Dáta sú uložené len na zariadení.

## Nasadenie na GitHub Pages

1. Na GitHube vytvor nový repozitár, napr. `akademia-hrdinov`.
2. *Add file → Upload files* a nahraj **obsah** tohto priečinka
   (`index.html`, `app.js`, `sw.js`, `manifest.webmanifest`, priečinok `icons`).
3. *Settings → Pages → Build and deployment*: Source **Deploy from a branch**,
   Branch **main**, priečinok **/ (root)** → Save.
4. Po chvíli bude appka na `https://<tvoje-meno>.github.io/akademia-hrdinov/`.

## Na tablete dieťaťa

Otvor odkaz a pridaj appku na plochu:
- **iPad (Safari):** Zdieľať → Pridať na plochu.
- **Android (Chrome):** menu ⋮ → Inštalovať aplikáciu / Pridať na plochu.

Appku spúšťaj z ikony na ploche. Safari maže dáta webov, ktoré sa 7 dní nepoužívajú,
ale appky pridané na plochu sa to netýka.

## Presun dát z verzie na claude.ai

1. V starej verzii: Tréner → Záloha a presun → **Kopírovať zálohu ako text**.
2. V novej verzii: Tréner → nastav PIN → Záloha a presun → vlož text → **Obnoviť zo zálohy**.
3. Po obnove platí PIN zo zálohy.

## Aktualizácia appky

Nahraj nové `index.html` a `app.js` do repozitára (prepísať). Keď je tablet online,
appka si pri ďalšom spustení načíta novú verziu. Dáta dieťaťa ostanú.

## Bezpečnosť

- Repozitár je verejný, preto doň nikdy nedávaj rozvrh, zálohy ani iné dáta dieťaťa.
  Tie patria len do appky a do zálohy uloženej v súkromí.
- Všetky appky na `<tvoje-meno>.github.io` zdieľajú jeden pôvod (origin). Používaj tam
  len appky, ktorým dôveruješ.
- Zálohu uchovávaj ako súkromnú. Obsahuje kresby, otázky dieťaťa aj odtlačok PINu.
