# Anleitung zum Veröffentlichen auf GitHub Pages

## Schritt 1: Repository erstellen
Gehe zu https://github.com/MarianaCannabis und erstelle ein neues Repository:
- Name: `terptrain-anleitung`
- Visibility: Public (für kostenlose GitHub Pages)
- README: Nein (haben wir schon)

## Schritt 2: Dateien hochladen
Lade diese Dateien hoch:
- `index.html` (die fertige Anleitung)
- `README.md`
- `.nojekyll`

Entweder per Drag & Drop im Browser oder per Git:
```bash
git init
git add .
git commit -m "Terptrain Anleitung v2.1"
git remote add origin https://github.com/MarianaCannabis/terptrain-anleitung.git
git push -u origin main
```

## Schritt 3: GitHub Pages aktivieren
1. Repository → Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: `main`, Folder: `/ (root)`
4. Klick auf "Save"

## Ergebnis
Nach 1-2 Minuten ist die Anleitung live unter:
**https://MarianaCannabis.github.io/terptrain-anleitung/**

## Updates veröffentlichen
Einfach die neue `index.html` hochladen und commiten – GitHub Pages aktualisiert automatisch.

