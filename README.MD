# Catch the Box — joc web demo

Un joc mic (HTML/CSS/JS) — click/tap pe cutiuță pentru a marca puncte. Scopul demo: exemplu simplu pentru a învăța Git/GitHub + publicare cu GitHub Pages.

## Structura
- `index.html` — jocul (un singur fișier)
- `LICENSE` — MIT
- `.gitignore` — fișiere ignorate

## Rulare local
1. Salvează `index.html` într-un folder, de ex. `catch-the-box`.
2. Deschide `index.html` în browser (dublu-click) sau rulează un server local, ex:
   - `python -m http.server 8000` (în folder) apoi vizitează `http://localhost:8000`.

## Git & GitHub (pași rapizi)
1. Inițializează repo local:
   ```bash
   cd catch-the-box
   git init
   git add .
   git commit -m "Initial commit: Catch the Box demo"

