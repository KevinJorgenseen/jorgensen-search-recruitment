# Clean rekrutteringsbyrå-side (statisk HTML/CSS)

Dette er en liten, rask og «eier-du-alt»-vennlig nettside.

## Innhold
- `index.html` – alt innhold/struktur
- `styles.css` – design (soft colors, skarpe kanter)
- `script.js` – mobilmeny + årstall
- `assets/` – legg inn bilder her

## Slik redigerer du
1. **Bytt navn**
   - Søk etter `Nordic Recruit` i `index.html` og erstatt med ditt byrånavn.
2. **Bytt e-post/telefon**
   - Søk etter `hei@dittbyra.no` og `+47 00 00 00 00 00`.
3. **Tilpass tekst**
   - Alle seksjoner er tydelig merket: Tjenester, Metode, Om, Kontakt.
4. **Legg inn portrett**
   - Legg et bilde i `assets/` og erstatt plassholderen i seksjonen `#om`.

## Lokal forhåndsvisning
Dobbeltklikk `index.html` eller kjør en enkel server:

```bash
python -m http.server 8000
```

Åpne: http://localhost:8000

## Hosting (gratis og enkelt)
- **Netlify**: dra og slipp mappen i Netlify Dashboard.
- **GitHub Pages**: push repo og aktiver Pages.

## Kontaktformular
Denne versjonen bruker `mailto:` for enklest mulig eierskap (ingen backend).
Hvis du vil ha ekte skjema (uten mailto), kan du bruke Netlify Forms eller en liten backend senere.
