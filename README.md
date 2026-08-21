# RetroTime — Floating Timer Widget

[English](README.md) | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

A minimalist glassmorphism floating timer widget with stopwatch, countdown, and Pomodoro modes. Fully offline, zero data collection.

> Chromium-based · Manifest V3 · No tracking · Offline-only · Customizable Colors

---

## Why RetroTime?

Most timer extensions open in a separate tab or popup. RetroTime floats directly on any webpage — drag it anywhere, snap to edges, minimize when not needed.

| Advantage | Detail |
|-----------|--------|
| ⏱️ **Triple Modes** | Stopwatch, custom countdown, Pomodoro (work+break cycle) |
| 🖱️ **Drag & Snap** | Smooth drag with edge-snapping and position memory |
| 🔔 **Multiple Sounds** | 3 built-in sounds (beep, chime, gentle) + upload your own |
| 📊 **History Tracking** | Auto-saves completed timers to track focus sessions |
| 🎚️ **Opacity Control** | 20%-100% transparency slider |
| 🔒 **Lock & Minimize** | Lock position to prevent drag, minimize to title bar |
| 🎨 **Custom Colors** | Change font color and background color (Premium) |
| 🌍 **Multi-Language** | EN, ZH, JA, DE, ES, FR |
| 🛡️ **Privacy First** | Only `storage` permission, fully offline |

---

## Free vs Premium

| Plan | Features |
|------|----------|
| **Free** | Stopwatch, countdown, Pomodoro, all sounds, opacity control, drag & snap, lock & minimize, history |
| **⭐ Premium** | Custom font color, custom background color |

All timer features are free forever. **Custom Colors** (font color + background color) require a VKT Premium license — a one-time purchase that supports development.

- 🛒 Get a license: `https://www.annmax1983.com/checkout.html?plugin=retrotime`
- ⚙ Activate it: open the popup → click the **🔒** button → enter your license key.

> License activation is **optional**. The free tier works fully without it.

---

## Preview

<p align="center">
  <img src="screenshot/promo.png" alt="RetroTime Preview" width="640">
</p>

---

## Supported Browsers

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Fully supported |
| Microsoft Edge | ✅ Fully supported |
| Other Chromium-based browsers | ✅ Should work |

---

## Installation

1. Open `chrome://extensions/` or `edge://extensions/`
2. Enable **Developer mode**
3. Click **Load unpacked** and select the project folder
4. Click the timer icon in your toolbar

---

## Usage

1. **Click the extension icon** to open settings
2. **Select mode** — Stopwatch, Countdown, or Pomodoro
3. **The timer widget** appears on the page — drag it anywhere
4. **▶ Start / ⏸ Pause / ↺ Reset** — control buttons on the widget
5. **⇄ Switch mode** — cycle through modes on the widget
6. **🔒 Lock** — prevent accidental dragging
7. **— Minimize** — collapse to title bar only

---

## Timer Modes

| Mode | Description |
|------|-------------|
| ⏱ **Stopwatch** | Count up from 00:00, no time limit |
| ⏳ **Countdown** | Set custom minutes (10/25/30/60 presets or custom), counts down to 00:00 |
| 🍅 **Pomodoro** | Work phase (default 25min) → Break phase (default 5min), auto-cycles |

---

## Privacy

- **storage** — Saves settings, position, and history locally
- **License (optional)** — Only if you activate a paid license: a device fingerprint + browser metadata is sent to `api.annmax1983.com` to activate/validate the license. This never includes your timer data or usage history.
- No network requests for free features — all processing happens locally
- Sound effects generated in-browser via Web Audio API
- [Privacy Policy](privacy-policy.html)

---

## Copyright Disclaimer

This extension provides a local floating timer overlay for user convenience. It does not modify, copy, or redistribute any website content.

---

## Source Code Notice

> ⚠️ **This repository does not publish source code.** It contains only usage documentation, release notes, and support resources. The extension is distributed exclusively through the Chrome Web Store. No offline installation packages or end-user source code are provided.

---

## License

Copyright © 2026 RetroTime. All rights reserved.
