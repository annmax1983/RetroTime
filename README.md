# RetroTime — Floating Timer Widget

[English](README.md) | [中文](languages/README_zh.md) | [Español](languages/README_es.md) | [Deutsch](languages/README_de.md) | [日本語](languages/README_ja.md) | [Français](languages/README_fr.md)

A minimalist glassmorphism floating timer widget with stopwatch, countdown, and Pomodoro modes. Fully offline, zero data collection.

> Chrome · Edge · Firefox · Manifest V3 · No tracking · Offline-only · Customizable Colors

---

## Why RetroTime?

Most timer extensions open in a separate tab or popup. RetroTime floats directly on any webpage — drag it anywhere, snap to edges, minimize when not needed.

| Advantage | Detail |
|-----------|--------|
| ⏱️ **Triple Modes** | Stopwatch, custom countdown, Pomodoro (work+break cycle) |
| 🖱️ **Drag & Snap** | Smooth drag with edge-snapping and position memory |
| 🔔 **Alerts & Sounds** | Desktop notifications, toolbar countdown badge, 3 built-in sounds (beep, chime, gentle) or upload your own |
| 📊 **History Tracking** | Auto-saves completed timers to track focus sessions |
| 🎚️ **Opacity Control** | 20%-100% transparency slider |
| 🔒 **Lock & Minimize** | Lock position to prevent drag, minimize to title bar |
| 🎨 **Custom Colors** | Change font color and background color (Premium) |
| 🌍 **Multi-Language** | EN, ZH, JA, DE, ES, FR |
| 🛡️ **Privacy First** | No data collection; `storage` + `alarms` + `notifications` only |

---

## Free vs Premium

| Plan | Features |
|------|----------|
| **Free** | Stopwatch, countdown, Pomodoro, all sounds, opacity control, drag & snap, lock & minimize, history |
| **⭐ Premium** | Custom font color, custom background color |

All timer features are free forever. **Custom Colors** (font color + background color) require a VKT Premium license — a one-time purchase that supports development.

- 🛒 Get a license: `https://www.annmax1983.com/checkout.html?plugin=retrotime`
- ⚙ Activate it: open the popup → click the **⚙** button (top right) → enter your license key.

> License activation is **optional**. The free tier works fully without it.

---

## Preview

<p align="center">
  <img src="screenshots/promo.png" alt="RetroTime Preview" width="640">
</p>

---

## Supported Browsers

| Browser | Status | Notes |
|---------|--------|-------|
| Google Chrome | ✅ Fully supported | Manifest V3 |
| Microsoft Edge | ✅ Fully supported | Manifest V3 |
| Mozilla Firefox | ✅ Fully supported | Manifest V3, Firefox 140+ (desktop) |
| Other Chromium-based browsers | ✅ Should work | Manifest V3 |

> **Firefox note:** the floating widget, drag & snap, all three modes, sounds, badge countdown, desktop notifications, history and Premium colours work the same way. The extension asks only for `storage`, `alarms`, `notifications`, `<all_urls>` (to draw the widget on pages) and the licence host.

---

## Installation

| Store | Link |
|---|---|
| Chrome Web Store | [Install for Chrome](https://chromewebstore.google.com/detail/cdboleaglibdjbogeofpcaodilmbljgp) |
| Microsoft Edge Add-ons | [Install for Edge](https://microsoftedge.microsoft.com/addons/detail/fbpjlhjnggfpfeakomkllgljbpegajbd) |
| Firefox Add-ons (AMO) | 🔜 Under review — link will be added once the listing is live |

> Install only from the official stores above — avoid third-party download sites.

---

## Usage

1. **Click the extension icon** to open settings
2. **Enable the widget** with the toggle in the header (off by default on first install)
3. **Select mode** — Stopwatch, Countdown, or Pomodoro
4. **The timer widget** appears on the page — drag it anywhere
5. **▶ Start / ⏸ Pause / ↺ Reset** — control buttons on the widget
6. **⇄ Switch mode** — cycle through modes on the widget
7. **🔒 Lock** — prevent accidental dragging
8. **— Minimize** — collapse to title bar only
9. **🔔 Desktop alerts** — system notification when time is up (works even when the browser is minimized); the toolbar icon shows remaining minutes

---

## Timer Modes

| Mode | Description |
|------|-------------|
| ⏱ **Stopwatch** | Count up from 00:00, no time limit |
| ⏳ **Countdown** | Set custom minutes (10/25/30/60 presets or custom), counts down to 00:00 |
| 🍅 **Pomodoro** | Custom work/break lengths (default 25min/5min), optional auto-continue, skip break |

---

## Privacy

- **storage** — Saves settings, position, and history locally
- **alarms** — Fires the timer completion exactly on time, even when no tab is visible
- **notifications** — Shows the desktop notification when a timer finishes
- **License (optional)** — Only if you activate a paid license: a random install identifier + browser metadata is sent to `api.annmax1983.com` to activate/validate the license. This never includes your timer data or usage history.
- No network requests for free features — all processing happens locally
- Sound effects generated in-browser via Web Audio API
- [Privacy Policy](privacy-policy.html)

---

## Copyright Disclaimer

This extension provides a local floating timer overlay for user convenience. It does not modify, copy, or redistribute any website content.

---

## Source Code Notice

> ⚠️ **This repository does not publish source code.** It contains only usage documentation, release notes, and support resources. The extension is distributed exclusively through the Chrome Web Store, Microsoft Edge Add-ons and Firefox Add-ons (AMO). No offline installation packages or end-user source code are provided.

---

## License

Copyright © 2026 RetroTime. All rights reserved.
