# Museum Herman De Cuyper — Website

Meertalige statische website voor het Museum Herman De Cuyper, Mechelsesteenweg 249, B-2830 Blaasveld (Willebroek).

## Structuur

```
/
├── index.html          ← Taalkeuzepagina (NL / FR / EN)
├── css/
│   └── style.css       ← Gedeelde stijlen (alle talen)
├── js/
│   └── nav.js          ← Hamburger menu
├── images/             ← Gedeelde afbeeldingen (alle talen)
├── nl/                 ← Nederlandse versie
│   ├── index.html
│   ├── museum.html
│   ├── biografie.html
│   ├── collectie.html
│   ├── evolutie.html
│   ├── klein-brabant.html
│   ├── activiteiten.html
│   ├── informatie.html
│   └── contact.html
├── fr/                 ← Franse versie (in te vullen)
│   └── *.html
└── en/                 ← Engelse versie (in te vullen)
    └── *.html
```

## Franse en Engelse vertalingen toevoegen

Wanneer de vertaalde HTML-bestanden beschikbaar zijn:
1. Vervang de placeholder-bestanden in `/fr/` en `/en/` door de echte vertalingen
2. Pas de paden aan: `../css/`, `../js/`, `../images/` (zelfde als NL)
3. Voeg de taalswitcher toe in de navigatie (zie NL-versie als voorbeeld)

## GitHub Pages activeren

1. Maak een repository aan op GitHub
2. Upload alle bestanden (mappen `nl/`, `fr/`, `en/`, `css/`, `js/`, `images/`)
3. Ga naar **Settings → Pages → Deploy from branch → main → / (root)**
4. De site is live op `https://gebruikersnaam.github.io/museum-herman-de-cuyper/`

## Eigen domein koppelen

1. Maak een bestand `CNAME` aan in de root met inhoud: `museumhermandecuyper.be`
2. Stel DNS in bij je registrar:
   - `A @ 185.199.108.153`
   - `A @ 185.199.109.153`
   - `A @ 185.199.110.153`
   - `A @ 185.199.111.153`
   - `CNAME www gebruikersnaam.github.io`
3. GitHub Pages → Custom domain → `museumhermandecuyper.be` → Enforce HTTPS

---
Conservator: Chris De Cuyper · info@museumhermandecuyper.be
