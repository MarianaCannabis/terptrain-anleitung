# GitHub Pages Einrichtung – Schritt für Schritt

## 🎯 Methode 1: EINFACH – „Deploy from branch" (empfohlen)

Diese Methode braucht KEINEN Workflow. Du stellst GitHub Pages einfach auf den main-Branch ein.

### Schritt 1: Repository erstellen
1. Gehe zu https://github.com/MarianaCannabis
2. Klicke auf das **+** oben rechts → „New repository"
3. Name: `terptrain-anleitung`
4. Visibility: **Public** ✓
5. „Create repository" klicken

### Schritt 2: Dateien hochladen
1. Im neuen Repository: Klicke „uploading an existing file"
2. Ziehe diese Dateien aus dem ZIP hinein:
   - `index.html`
   - `index-en.html`, `index-tr.html`, etc.
   - `manifest.json`
   - `icon-192.png`, `icon-512.png`
   - `.nojekyll` ← WICHTIG! (versteckte Datei, sicherstellen dass sie dabei ist)
3. Commit message: „Terptrain Anleitung v2"
4. „Commit changes" klicken

### Schritt 3: GitHub Pages aktivieren
1. Repository → **Settings** (oben rechts)
2. Links in der Sidebar: **Pages** klicken
3. Unter „Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
4. **Save** klicken
5. Warten (~2 Minuten) → Seite erscheint unter:
   **https://MarianaCannabis.github.io/terptrain-anleitung/**

---

## 🔧 Methode 2: GitHub Actions (automatisches Deployment)

Falls du bereits ein Repository hast:

### Problem: „Run workflow" nicht sichtbar?
→ Der „Run workflow" Button erscheint NUR wenn:
1. Die Datei `.github/workflows/deploy.yml` bereits auf dem **main**-Branch ist
2. UND Pages auf **„GitHub Actions"** eingestellt ist

### Lösung:
1. Repository → **Settings → Pages**
2. Source von „Deploy from a branch" auf **„GitHub Actions"** ändern
3. Save klicken
4. Jetzt: **Actions** Tab oben
5. Links: „Deploy to GitHub Pages" klicken
6. Rechts: **„Run workflow"** Button erscheint jetzt!
7. Auf den grünen Button klicken → Deployment startet

### Alternativ: einfach eine Datei ändern
Wenn du die `index.html` nochmal hochlädst (neu commitest), startet der Workflow automatisch!

---

## ✅ Testen ob es funktioniert
Öffne: https://MarianaCannabis.github.io/terptrain-anleitung/

Falls 404: Warte noch 2-5 Minuten nach dem ersten Deployment.
