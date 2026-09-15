# Giacomo Tornello — Sito personale

Sito di presentazione e portfolio di **Giacomo Tornello**, freelance digitale
(marketing, project management, Scrum Master, QA, sviluppo web).

Basato su **Astro** (tema "Michael — Portfolio Theme for Designers" come reference
strutturale). Dominio: [giacomotornello.com](https://giacomotornello.com).

## Stack

- [Astro](https://astro.build) v7+

## Sviluppo

```bash
npm install
npm run dev        # server locale
npm run build      # build di produzione
npm run preview    # anteprima build
```

## Struttura

```
src/
  layouts/Layout.astro   # layout globale + header/footer + SEO
  data/site.ts           # contenuti centralizzati (testi, progetti, esperienze)
  pages/
    index.astro          # Home
    about.astro          # Chi sono
    works.astro          # Progetti
    contact.astro        # Contatti
    licenses.astro       # Licenze
```

## Contenuti

Tutti i testi, i progetti, le esperienze e i contatti sono in
`src/data/site.ts` — modifica lì per aggiornare il sito senza toccare il markup.

## Note

- Foto ritratto: placeholder sostituibile (nessuna foto definitiva ancora).
- Testimonianze: sezione non presente (riattivabile in futuro).
- Social: solo link verificati (LinkedIn, Instagram).
