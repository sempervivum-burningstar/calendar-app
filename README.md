# 📅 Calendar App — Electron

![Electron](https://img.shields.io/badge/Electron-33.4-black?logo=electron)
![Tests](https://img.shields.io/badge/tests-35%20passing-brightgreen)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-blue)

**One command to run:** `npm start` — clean Month view, zero config, data survives reinstalls.


### 🚀 Quick Start

```bash
git clone https://github.com/sempervivum-burningstar/calendar-app
cd calendar-app
npm install
npm start
# or npm test  → 35 recurrence tests
```

> Requires Node.js 18+. Data path shown in sidebar footer.

### 🎮 Tour

| Action | How |
|--------|-----|
| Select day | Click cell |
| Add event | Double-click day · `Enter` · `+ New event` |
| Edit | Pencil icon or double-click event |
| Search | Type in top bar or press `/` |
| Toggle type | Click left sidebar chip |
| Edit types | `Manage…` → color picker / rename inline |

### 🧩 Structure

| File | Purpose |
|------|---------|
| `main.js` | Electron main, `userData` persistence + migration |
| `preload.js` | Safe IPC bridge |
| `recurrence.js` | Recurrence engine (shared with tests) |
| `renderer.js` | UI + search + editable types |
| `index.html` | Layout & dialogs |

---

### 🌟 Love it? Star it & share

- ⭐ Star this repo — helps others discover it
- 🤝 PRs / Issues welcome — see `CONTRIBUTING.md`

---

Built with Electron • Catppuccin-inspired dark theme
