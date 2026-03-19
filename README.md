# 💖 Our Love Train — Setup Guide

A romantic interactive web experience for Siwe. No build tools required!

---

## ▶️ Running Locally

### Option 1: Just open the file
Double-click `index.html` in your file manager — it opens directly in any modern browser.

> **Note:** Audio requires a user interaction first (browser policy). Click the 🔊 button top-right to unmute.

### Option 2: Local server (recommended for audio)
```bash
# Python 3
python3 -m http.server 8080
# Then open: http://localhost:8080
```

---

## 🚀 Deploy to Vercel (Free)

### One-command deploy:
```bash
npm i -g vercel
vercel --name love-journey
```
Select the folder containing `index.html` when prompted.

### Or drag & drop:
1. Go to [vercel.com](https://vercel.com) → New Project
2. Drag & drop the `love-journey` folder
3. Click **Deploy** — done! ✨

### Or GitHub Pages:
1. Create a new GitHub repo
2. Upload `index.html`
3. Go to Settings → Pages → Deploy from main branch

---

## 🎮 Experience Flow

1. **Landing** — Typewriter message + pulsing heart button
2. **Modal 1** — "Do you love me?" (escaping No button)
3. **Modal 2** — "Will you allow me to love you forever?" (same mechanic)
4. **Modal 3** — Cosmic love quiz with dropdown
5. **Scratch Card** — Reveal the hidden love letter
6. **Completion** — Confetti + heart explosion 💖

---

## 🔧 Customisation

All text/content is in `index.html`:
- `HIDDEN_MSG` — the final love letter
- Typewriter text — in `renderLanding()`
- Modal questions — in `renderModal1/2/3()`
- Floating objects — in `spawnObjects()`

---

Made with 💖 for Siwe
