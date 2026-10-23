# RetroTime — Schwebendes Timer-Widget

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | Deutsch | [日本語](README_ja.md) | [Français](README_fr.md)

Ein minimalistisches Glassmorphism-Timer-Widget mit Stoppuhr, Countdown und Pomodoro-Modus. Vollständig offline, null Datensammlung.

> Chromium-basiert · Manifest V3 · Kein Tracking · Nur offline · Anpassbare Farben

---

## Warum RetroTime?

Die meisten Timer-Erweiterungen öffnen sich in einem separaten Tab oder Popup. RetroTime schwebt direkt auf jeder Webseite — ziehe es beliebig hin, es rastet an Rändern ein und lässt sich minimieren.

| Vorteil | Details |
|---------|---------|
| ⏱️ **Drei Modi** | Stoppuhr, benutzerdefinierter Countdown, Pomodoro (Arbeits+Pause-Zyklus) |
| 🖱️ **Ziehen & Einrasten** | Sanftes Ziehen mit Kanteneinrastung und Positionsspeicher |
| 🔔 **Alarme & Töne** | Desktop-Benachrichtigungen, Toolbar-Countdown-Badge, 3 eingebaute Sounds (Piepen, Glocke, Sanft) oder eigene hochladen |
| 📊 **Verlaufsverfolgung** | Speichert abgeschlossene Timer automatisch, um Fokussitzungen nachzuverfolgen |
| 🎚️ **Transparenz-Regler** | 20%-100% Schieberegler |
| 🔒 **Sperren & Minimieren** | Position sperren, um Ziehen zu verhindern, auf Titelleiste minimieren |
| 🎨 **Eigene Farben** | Schriftfarbe und Hintergrundfarbe ändern (Premium) |
| 🌍 **Mehrsprachig** | EN, ZH, JA, DE, ES, FR |
| 🛡️ **Datenschutz zuerst** | Keine Datensammlung; nur `storage` + `alarms` + `notifications` |

---

## Kostenlos vs. Premium

| Plan | Funktionen |
|------|-----------|
| **Kostenlos** | Stoppuhr, Countdown, Pomodoro, alle Töne, Transparenz-Regler, Ziehen & Einrasten, Sperren & Minimieren, Verlauf |
| **⭐ Premium** | Eigene Schriftfarbe, eigene Hintergrundfarbe |

Alle Timer-Funktionen sind für immer kostenlos. **Eigene Farben** (Schriftfarbe + Hintergrundfarbe) erfordern eine VKT Premium-Lizenz — ein einmaliger Kauf, der die Entwicklung unterstützt.

- 🛒 Lizenz erhalten: `https://www.annmax1983.com/checkout.html?plugin=retrotime`
- ⚙ Aktivieren: Popup öffnen → **⚙**-Button klicken (oben rechts) → Lizenzschlüssel eingeben.

> Die Lizenzaktivierung ist **optional**. Die kostenlose Stufe funktioniert vollständig ohne sie.

---

## Vorschau

<p align="center">
  <img src="../screenshots/promo.png" alt="RetroTime Vorschau" width="640">
</p>

---

## Unterstützte Browser

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Vollständig unterstützt |
| Microsoft Edge | ✅ Vollständig unterstützt |
| Andere Chromium-basierte Browser | ✅ Sollte funktionieren |

---

## Installation

| Store | Link |
|---|---|
| Chrome Web Store | [In Chrome installieren](https://chromewebstore.google.com/detail/cdboleaglibdjbogeofpcaodilmbljgp) |
| Microsoft Edge Add-ons | [In Edge installieren](https://microsoftedge.microsoft.com/addons/detail/fbpjlhjnggfpfeakomkllgljbpegajbd) |

> Installieren Sie nur über die offiziellen Stores oben – meiden Sie Download-Seiten Dritter.

---

## Verwendung

1. **Auf das Erweiterungssymbol klicken**, um die Einstellungen zu öffnen
2. **Widget aktivieren** mit dem Schalter im Header (bei Erstinstallation standardmäßig aus)
3. **Modus wählen** — Stoppuhr, Countdown oder Pomodoro
4. **Das Timer-Widget** erscheint auf der Seite — ziehe es beliebig hin
5. **▶ Start / ⏸ Pause / ↺ Reset** — Steuerungsbuttons auf dem Widget
6. **⇄ Modus wechseln** — Modi auf dem Widget durchschalten
7. **🔒 Sperren** — versehentliches Ziehen verhindern
8. **— Minimieren** — auf die Titelleiste einklappen
9. **🔔 Desktop-Alarme** — Systembenachrichtigung bei Zeitablauf (funktioniert auch bei minimiertem Browser); das Toolbar-Symbol zeigt verbleibende Minuten an

---

## Timer-Modi

| Modus | Beschreibung |
|-------|--------------|
| ⏱ **Stoppuhr** | Aufwärts ab 00:00, kein Zeitlimit |
| ⏳ **Countdown** | Eigene Minuten einstellen (10/25/30/60 Voreinstellungen oder eigene), zählt bis 00:00 herunter |
| 🍅 **Pomodoro** | Eigene Arbeits-/Pausenlängen (Standard 25min/5min), optional Auto-Weiter, Pause überspringen |

---

## Datenschutz

- **storage** — Speichert Einstellungen, Position und Verlauf lokal
- **alarms** — Löst den Timer-Abschluss pünktlich aus, auch wenn kein Tab sichtbar ist
- **notifications** — Zeigt die Desktop-Benachrichtigung bei Timer-Ende
- **Lizenz (optional)** — Nur bei Aktivierung einer kostenpflichtigen Lizenz: Lizenzschlüssel und eine zufällige Installationskennung + Browser-Metadaten werden an `api.annmax1983.com` gesendet, um die Lizenz zu aktivieren/validieren. Dies enthält nie deine Timer-Daten oder Nutzungsverlauf.
- Keine Netzwerk-Anfragen für kostenlose Funktionen — alles passiert lokal
- Sound-Effekte werden im Browser via Web Audio API generiert
- [Datenschutzerklärung](privacy-policy.html)

---

## Urheberrechtshinweis

Diese Erweiterung bietet ein lokales schwebendes Timer-Overlay zur Bequemlichkeit des Nutzers. Sie verändert, kopiert oder verbreitet keinen Website-Inhalt.

---

## Quellcode-Hinweis

> ⚠️ **Dieses Repository veröffentlicht keinen Quellcode.** Es enthält nur Nutzerdokumentation, Versionshinweise und Support-Ressourcen. Die Erweiterung wird ausschließlich über den Chrome Web Store vertrieben. Es werden keine Offline-Installationspakete oder Endbenutzer-Quellcodes bereitgestellt.

---

## Lizenz

Copyright © 2026 RetroTime. Alle Rechte vorbehalten.
