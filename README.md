# Salta! – biglietto di compleanno

Un gioco in stile Doodle Jump: scegli il personaggio, salta di piattaforma in piattaforma
ed evita i nemici. Ogni 100 punti compare una lettera, a 1000 punti si legge **AUGURI VERO**.

## Come pubblicarlo con GitHub Pages
1. Crea un nuovo repository su GitHub (es. `salta`), pubblico.
2. Carica i file di questa cartella (`index.html`, le icone `.png` e `favicon.ico`, `manifest.webmanifest`, `.nojekyll`, `README.md`) con **Add file → Upload files**.
3. Vai su **Settings → Pages**. In *Build and deployment* scegli **Deploy from a branch**, branch **main**, cartella **/ (root)** e salva.
4. Dopo circa un minuto il gioco è online su `https://TUO-NOME-UTENTE.github.io/salta/`.

## Su iPhone
Apri il link in Safari, tocca **Condividi → Aggiungi alla schermata Home**: si apre a schermo intero come un'app.

## Personalizzare
- **Schermata finale:** in `index.html` cerca `<div id="win">` e sostituisci il testo con un tag `<img>`.
- **Frequenza nemici:** cerca `R()<0.035+diff*0.06`.
- **Personaggi:** sono immagini incorporate nell'oggetto `SPR`.
