# 🎬 watchpicker

> Stop scrolling. Let fate decide.

A minimal, browser-based app that randomly picks a movie or TV series from your personal watchlist — so you stop wasting time deciding and start actually watching.

---

## ✨ Features

- **Split lists** — separate libraries for Movies and TV Series
- **Mood picker** — choose between a Movie or TV Series before each spin
- **Slot machine animation** — titles cycle and slow down before landing on a pick
- **Removal preferences** — auto-remove picked titles, or manage your library yourself
- **Pick history** — timestamped log of everything fate has chosen for you
- **No account needed** — everything lives in your browser's local storage
- **Zero dependencies** — single `.html` file, works offline

---

## 🚀 Getting Started

No install, no build step. Just open the file.

```bash
git clone https://github.com/your-username/watchpicker.git
cd watchpicker
open what-to-watch.html   # macOS
# or double-click the file in any file explorer
```

Or host it anywhere static — GitHub Pages, Netlify, Vercel, etc.

---

## 📦 Stack

| Layer   | Tech                          |
|---------|-------------------------------|
| UI      | Vanilla HTML + CSS            |
| Logic   | Vanilla JavaScript (ES6+)     |
| Storage | Browser `localStorage`        |
| Hosting | Any static host / local file  |

No frameworks. No bundler. No backend.

---

## 💾 Data & Storage

All data is stored in your browser's `localStorage`. This means:

- ✅ No server, no account, no tracking
- ⚠️ Clearing your browser data or site storage **will delete your list**
- ⚠️ Your list is **browser-specific** — it won't appear in other browsers or devices

---

## 📱 React Native Version

A React Native (Expo) version targeting iOS and Android is included in the `/WhatToWatch` directory.

```bash
cd WhatToWatch
npm install
npx expo start
```

Requires [Expo Go](https://expo.dev/go) on your device to preview.

---

## 🗂️ Project Structure

```
watchpicker/
├── what-to-watch.html      # The entire web app (single file)
└── WhatToWatch/            # React Native / Expo app
    ├── App.js
    ├── app.json
    ├── package.json
    └── src/
        ├── HomeScreen.js
        ├── storage.js
        ├── theme.js
        └── components/
            ├── WelcomeModal.js
            ├── LibraryModal.js
            ├── AddModal.js
            └── PrefsModal.js
```

---

## 🛠️ Built by

**Binuka** — with a little help from [Claude](https://claude.ai)

---

## 📄 License

MIT — do whatever you want with it.
