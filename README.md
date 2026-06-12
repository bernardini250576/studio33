# Studio 33 — Restyling (bozza dimostrativa)

Anteprima di restyling **non ufficiale** per [studio33club.com](https://studio33club.com/), ispirata all'estetica di Oswalds Mill Audio. Single-page, bilingue IT/EN, zero dipendenze di build.

> ⚠️ **Bozza a scopo dimostrativo.** Non affiliata né approvata ufficialmente da Studio 33 / The Lens srls. Immagini e contenuti sono © dei rispettivi proprietari e mostrati solo a scopo illustrativo.

## Anteprima

Pubblicabile su GitHub Pages: abilita Pages → branch `main` → root. La home è `index.html`.

## Caratteristiche

- **Single file** — tutto in `index.html` (HTML + CSS + JS inline)
- **Bilingue** IT/EN con toggle istantaneo (nessun reload)
- **6 sezioni** — Home, Hi-End Audio, Location, Produzione, Formazione, Resonance
- **Responsive** fino a mobile
- **Accessibile** — focus-visible, prefers-reduced-motion, attributi lang
- **Privacy-friendly** — nessun cookie, tracker o analytics

## Privacy / GDPR

Questa anteprima **non raccoglie dati personali**, non usa cookie e non effettua profilazione. Carica però risorse esterne necessarie al rendering, che possono registrare l'indirizzo IP del visitatore secondo le rispettive informative:

| Risorsa | Fornitore | Dato trasmesso |
|---|---|---|
| Font (Playfair Display, EB Garamond) | Google Fonts | IP |
| Icone | jsDelivr (Tabler Icons) | IP |
| Immagini | WordPress.com CDN (Automattic) | IP |

Un banner informativo lo segnala al primo accesso. **Per la pubblicazione definitiva** si raccomanda di self-hostare font e icone, così da eliminare ogni trasmissione dati verso terzi.

## Struttura

```
index.html      # la pagina (unico file necessario)
.nojekyll       # disabilita Jekyll su GitHub Pages
.gitignore
README.md
```

## Tecnologie

HTML5 · CSS3 (variabili custom) · Vanilla JS · Google Fonts · Tabler Icons (pinned `@3.31.0`)

## Licenza

Codice del restyling: uso dimostrativo. Contenuti, marchi e immagini di Studio 33 restano dei rispettivi titolari.
