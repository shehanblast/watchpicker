# 🎬 watchpicker

> Stop scrolling. Let fate decide.

A minimal, browser-based app that randomly picks a movie or TV series from your personal watchlist — so you stop wasting time deciding and start actually watching.

## ✨ Features

- **Split lists** — separate libraries for Movies and TV Series
- **Mood picker** — choose between a Movie or TV Series before each spin
- **Slot machine animation** — titles cycle and slow down before landing on a pick
- **Pre-loaded samples** — comes with curated sample movies and TV series; add your own or remove the defaults via the library
- **Removal preferences** — auto-remove picked titles, or manage your library yourself
- **Pick history** — timestamped log of everything fate has chosen for you
- **No account needed** — everything lives in your browser's local storage
- **Zero dependencies** — single `.html` file, works offline

## 📦 Stack

| Layer   | Tech                         |
| ------- | ---------------------------- |
| UI      | Vanilla HTML + CSS           |
| Logic   | Vanilla JavaScript (ES6+)    |
| Storage | Browser `localStorage`       |
| Hosting | Any static host / local file |

No frameworks. No bundler. No backend.

---

## 💾 Data & Storage

All data is stored in your browser's `localStorage`. This means:

- ✅ No server, no account, no tracking
- ⚠️ Clearing your browser data or site storage **will delete your list**
- ⚠️ Your list is **browser-specific** — it won't appear in other browsers or devices

## 🛠️ Built by

**Binuka** — with a little help from [Claude](https://claude.ai)
