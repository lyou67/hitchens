# Roster

PWA installable sur iPhone via GitHub Pages.

## Deploy

1. Push ce repo sur GitHub
2. Settings → Pages → Source: `main` branch, `/ (root)`
3. Ton app sera dispo sur `https://TON-USERNAME.github.io/roster/`

## Installer sur iPhone

1. Ouvre l'URL dans Safari
2. Partager → "Sur l'écran d'accueil"
3. L'app s'installe comme une vraie app, plein écran, sans barre Safari

## Structure

```
roster/
├── index.html       # App complète
├── manifest.json    # Config PWA
├── sw.js            # Service worker (offline)
└── assets/
    ├── icon-32.png
    ├── icon-180.png  ← icône iPhone
    ├── icon-192.png
    └── icon-512.png
```

## Données

Stockées en `localStorage` sur l'appareil. Rien ne part sur un serveur.
