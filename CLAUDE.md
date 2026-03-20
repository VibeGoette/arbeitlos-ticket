# CLAUDE.md — arbeitlos-ticket

## Projekt

Interaktive AI-Aufklärungsseite. Single-File HTML/CSS/JS. Deployed auf Vercel.

## Architektur

- `index.html` — Komplette Seite (HTML + CSS + JS inline)
- Three.js r128 via CDN (3D Hero)
- Chart.js 4.4.0 via CDN (Visualisierungen)
- Google Fonts: Fraunces (Display) + Plus Jakarta Sans (Body)
- Dark/Light Theme via `data-theme` Attribut auf `<html>`

## Design Tokens

Warm-Dark Palette: `--color-bg: #0D0906`, Accent: `#FF6B35`, Surface: `#1E1411`.
Light Theme invertiert. CSS Custom Properties in `:root`.

## Konventionen

- Deutsch für allen Content, Englisch für Code-Kommentare
- Keine Emojis in UI-Elementen (Text-Emojis im Content sind OK als Stilmittel)
- Quellen als Fußnoten mit Rückverweisen (`[↑]`)
- Scroll-Animationen via `.reveal` Klasse + IntersectionObserver
- Charts: Canvas-IDs `jobChart`, `medChart`, `unemploymentChart`

## Deployment

- **Vercel** — auto-deploy from `main` branch
- **Team:** team_lzerLSOOXoO3cZdlpBhqA1MJ
- **Repo:** VibeGoette/arbeitlos-ticket
- **Domain:** arbeitlos-ticket.vercel.app

## Git

```bash
git config user.email "designedbygotti@gmail.com"
git config user.name "VibeGoette"
```

## Wichtig

- v1-archive/ NICHT anfassen — das ist das Original
- robots.txt und sitemap.xml aktuell halten bei neuen Seiten
- Keine externen Tracking-Scripts ohne Consent
