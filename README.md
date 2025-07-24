# Asker Skadedyrkontroll - Homepage

En enkel og moderne hjemmeside for Asker Skadedyrkontroll bygget med HTML, CSS og JavaScript.

## Filstruktur

```
asker-skadedyrkontroll/
├── index.html          (forsiden)
├── pages/
│   ├── about.html       (om oss)
│   ├── services.html    (tjenester)
│   └── contact.html     (kontakt)
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── README.md
└── README.md
```

## Funksjoner

- 🎨 **Enkel Design**: Ryddig og profesjonell design
- 📱 **Responsiv**: Fungerer på alle enheter
- ⚡ **Rask**: Lettvekt og optimalisert for ytelse
- 📝 **Kontaktskjema**: Funksjonelt kontaktskjema
- 🧭 **Navigasjon**: Smooth scrolling og mobilvennlig navigasjon
- 🌍 **Norsk Språk**: Innhold på norsk for lokalt marked

## Kom i Gang

### Forutsetninger

- En nettleser (Chrome, Firefox, Safari, Edge)
- Tekstredigerer (VS Code, Sublime Text, etc.)

### Installasjon

1. **Last ned eller klon prosjektet**
2. **Åpne `index.html` i nettleseren**
   - Dobbeltklikk på `index.html` filen
   - Eller dra filen inn i nettleseren

### Alternativ: Lokal Server (Anbefalt)

For beste opplevelse, bruk en lokal server:

#### Med Python:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Med Node.js:

```bash
npx serve .
```

#### Med PHP:

```bash
php -S localhost:8000
```

Deretter åpne `http://localhost:8000` i nettleseren.

## Tilpasning

### Innhold

- Rediger HTML-filene for å endre tekst, bilder og struktur
- Oppdater kontaktinformasjon, tjenester og bedriftsdetaljer

### Styling

- CSS-klasser brukes gjennom hele HTML-en
- Fargepaletten kan endres i `css/style.css`
- Modifiser fargeskjemaet ved å endre `primary` og `secondary` fargene

### Funksjonalitet

- JavaScript-funksjonalitet er i `js/script.js`
- Legg til nye funksjoner ved å utvide eksisterende JavaScript

## Bilder

Se `images/README.md` for informasjon om hvilke bilder som trengs og retningslinjer for bilder.

## Kontaktskjema

Kontaktskjemaet viser for øyeblikket en suksessmelding. For å gjøre det fullt funksjonelt:

1. **Legg til e-postfunksjonalitet** med tjenester som Formspree eller Netlify Forms
2. **Legg til databaseslagring** for kontaktskjema-innsendinger
3. **Legg til spam-beskyttelse** med reCAPTCHA

## Legge til Express senere

Hvis du senere ønsker å legge til en backend med Express:

1. **Installer Node.js og npm**
2. **Opprett `package.json`**:
   ```bash
   npm init -y
   npm install express
   ```
3. **Opprett `server.js`** for å serve statiske filer
4. **Oppdater kontaktskjemaet** til å sende data til backend

## SEO-optimalisering

Hjemmesiden inkluderer:

- Riktige meta-tagger
- Semantisk HTML-struktur
- Responsivt design
- Raske lastetider

For bedre SEO:

1. Legg til flere meta-tagger
2. Implementer strukturerte data
3. Legg til en sitemap
4. Sett opp Google Analytics

## Nettleserstøtte

- Chrome (siste versjon)
- Firefox (siste versjon)
- Safari (siste versjon)
- Edge (siste versjon)
- Mobilnettlesere

## Lisens

MIT Lisens - føl deg fri til å bruke denne malen for dine egne prosjekter.

## Støtte

For spørsmål eller problemer, vennligst kontakt utviklingsteamet.

---

**Bygget med ❤️ for Asker Skadedyrkontroll**
