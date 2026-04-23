# ⌨️ KeyBind Launcher

A premium cross-platform desktop productivity app that lets you assign applications and websites to any keyboard shortcut — with a fully interactive visual keyboard, RGB theme engine, multi-profile support, and silent system tray operation.

Built with **Electron + React**. Works on Windows, macOS, and Linux.

---

![Version](https://img.shields.io/badge/version-2.0.0-818cf8?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-06b6d4?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-10b981?style=flat-square)
![Electron](https://img.shields.io/badge/electron-28-47848f?style=flat-square&logo=electron)

---

## ✨ Features

- **Visual Keyboard UI** — Click any key on a full QWERTY keyboard to assign actions
- **Key Combinations** — Support for Ctrl / Alt / Shift / Win modifier combos
- **Multi-Action Keys** — Each key can open multiple apps AND multiple URLs
- **Launch Delay** — Configurable delay between each launch (0–3000ms)
- **Global Shortcuts** — Shortcuts fire even when the app is minimized or hidden
- **System Tray** — Runs silently in the background, never truly closed
- **Startup Launch** — Registers with OS to launch automatically at login
- **Theme Engine** — 4 built-in themes with real-time switching, no reload required
- **Profile System** — Separate keybind sets for Work, Study, Gaming, and more
- **Dashboard** — Stats cards, recent activity feed, and quick-launch grid
- **Color-Coded Keys** — Each binding gets its own neon color indicator and glow
- **Import / Export** — Share your configs as portable JSON files

---

## 🎨 Themes

| Theme | Description |
|---|---|
| **Cyberpunk** | Deep indigo, electric violet glow, grid lines, scan-line texture |
| **Neon RGB** | Pitch black, neon green + hot pink, ultra-bright accents |
| **Minimal Dark** | Refined charcoal, monochrome typography, no distractions |
| **Minimal Light** | Paper white, ink-black text, clean editorial feel |

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org) v18 or higher
- npm (included with Node)

### Install & Run

```bash
# Clone the repo
git clone https://github.com/Nathul/Key_Bind-Launcher.git
cd Key_Bind-Launcher

# Install dependencies
npm install

# Start the app
npm start

# Start with DevTools open
npm run dev
```

> **Note:** The renderer loads React 18 and Babel from CDN on first launch.
> After that, they are cached and the app works fully offline.

---

## 📖 How to Use

### Assigning a shortcut
1. Open the app — the visual keyboard is shown by default
2. Optionally click **Ctrl / Alt / Shift** first to build a key combo (they highlight)
3. Click any regular key — the config panel slides in
4. Add apps (file picker) and/or website URLs
5. Choose a color, set an optional delay, click **Save**
6. The key now glows and the shortcut is live globally

### Profiles
Switch between Work, Study, Gaming, or any custom profile using the left sidebar.
Each profile has its own independent set of keybinds.
Switching profiles instantly re-registers shortcuts — the previous profile's shortcuts stop working immediately.

### System Tray
The app minimizes to your system tray and stays running.
Right-click the tray icon to show the window, reload shortcuts, toggle startup, or quit.

---


<img width="1736" height="1012" alt="image" src="https://github.com/user-attachments/assets/22fc6240-413d-458d-b492-e1b0500edfe9" />
