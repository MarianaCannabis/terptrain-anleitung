# Terptrain Mitglieder-Anleitung

Interaktive Mitglieder-Anleitung für die Terptrain Community-Plattform.

## 🌍 Sprachen / Languages

| Sprache | URL |
|---------|-----|
| 🇩🇪 Deutsch (Standard) | `https://MarianaCannabis.github.io/terptrain-anleitung/` |
| 🇬🇧 English | `https://MarianaCannabis.github.io/terptrain-anleitung/index-en.html` |
| 🇹🇷 Türkçe | `https://MarianaCannabis.github.io/terptrain-anleitung/index-tr.html` |
| 🇫🇷 Français | `https://MarianaCannabis.github.io/terptrain-anleitung/index-fr.html` |
| 🇪🇸 Español | `https://MarianaCannabis.github.io/terptrain-anleitung/index-es.html` |
| 🇳🇱 Nederlands | `https://MarianaCannabis.github.io/terptrain-anleitung/index-nl.html` |
| 🇵🇱 Polski | `https://MarianaCannabis.github.io/terptrain-anleitung/index-pl.html` |

## ✨ Features

- 38 Kapitel · 51 Screenshots · 2,6 MB
- Dark/Light Mode · 6 Akzentfarben
- 8 Sprachen (DE/EN/TR/FR/ES/NL/PL/AR)
- Offline-fähig (PWA) · Installierbar
- Lesezeichen · Notizen · Fortschritt-Tracking
- Quiz · Lernpfade · Glossar
- Leselineal · Fokus-Modus · Zeilenabstand
- Keyboard Shortcuts · Suche · Statistik

## 🚀 Deployment

Automatisch via GitHub Actions – jeder Push auf `main` deployt sofort.

### Einmalige Einrichtung:
1. Repo `terptrain-anleitung` auf https://github.com/MarianaCannabis anlegen
2. **Settings → Pages → Source: "GitHub Actions"** aktivieren
3. Diese Dateien pushen → fertig!

```bash
git init
git add .
git commit -m "Terptrain Anleitung v2.2"
git remote add origin https://github.com/MarianaCannabis/terptrain-anleitung.git
git push -u origin main
```

## 📁 Dateien

```
index.html          ← Deutsche Hauptversion
index-en.html       ← English
index-tr.html       ← Türkçe
index-fr.html       ← Français
index-es.html       ← Español
index-nl.html       ← Nederlands
index-pl.html       ← Polski
manifest.json       ← PWA Manifest
icon-192.png        ← PWA Icon
icon-512.png        ← PWA Icon (groß)
.nojekyll           ← GitHub Pages: Jekyll deaktiviert
.github/workflows/  ← Auto-Deploy Workflow
```

**Version 2.2 · April 2026**
