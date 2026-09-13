# RetroTime — Widget minuteur flottant

[English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | Français

Un widget minuteur flottant minimalist en glassmorphism avec modes chronomètre, compte à rebours et Pomodoro. Entièrement hors ligne, zéro collecte de données.

> Chromium · Manifest V3 · Aucun suivi · Hors ligne uniquement · Couleurs personnalisables

---

## Pourquoi RetroTime ?

La plupart des extensions de minuteur s'ouvrent dans un onglet ou un popup séparé. RetroTime flotte directement sur n'importe quelle page web — glissez-le où vous voulez, collez-le aux bords, minimisez-le quand vous n'en avez pas besoin.

| Avantage | Détail |
|-----------|--------|
| ⏱️ **Triple mode** | Chronomètre, compte à rebours personnalisé, Pomodoro (cycle travail + pause) |
| 🖱️ **Glisser et coller** | Déplacement fluide avec aimantation aux bords et mémorisation de la position |
| 🔔 **Alertes et sons** | Notifications bureau, badge de compte à rebours dans la barre d'outils, 3 sons intégrés (bip, carillon, doux) ou importez les vôtres |
| 📊 **Historique** | Sauvegarde automatique des minuteurs terminés pour suivre vos sessions de concentration |
| 🎚️ **Contrôle d'opacité** | Curseur de transparence de 20 % à 100 % |
| 🔒 **Verrouiller et minimiser** | Verrouillez la position pour éviter les déplacements, minimisez en barre de titre |
| 🎨 **Couleurs personnalisables** | Changez la couleur du texte et du fond (Premium) |
| 🌍 **Multilingue** | EN, ZH, JA, DE, ES, FR |
| 🛡️ **Confidentialité avant tout** | Aucune collecte de données ; `storage` + `alarms` + `notifications` uniquement |

---

## Gratuit vs Premium

| Plan | Fonctionnalités |
|------|----------|
| **Gratuit** | Chronomètre, compte à rebours, Pomodoro, tous les sons, contrôle d'opacité, glisser et coller, verrouiller et minimiser, historique |
| **⭐ Premium** | Couleur de texte personnalisée, couleur de fond personnalisée |

Toutes les fonctionnalités de minuteur sont gratuites à vie. Les **Couleurs personnalisables** (couleur du texte + couleur de fond) nécessitent une licence VKT Premium — un achat unique qui soutient le développement.

- 🛒 Obtenir une licence : `https://www.annmax1983.com/checkout.html?plugin=retrotime`
- ⚙ L'activer : ouvrez le popup → cliquez sur le bouton **⚙** (en haut à droite) → saisissez votre clé de licence.

> L'activation de la licence est **optionnelle**. Le niveau gratuit fonctionne entièrement sans elle.

---

## Aperçu

<p align="center">
  <img src="screenshot/promo.png" alt="Aperçu RetroTime" width="640">
</p>

---

## Navigateurs compatibles

| Navigateur | Statut |
|---------|--------|
| Google Chrome | ✅ Entièrement pris en charge |
| Microsoft Edge | ✅ Entièrement pris en charge |
| Autres navigateurs basés sur Chromium | ✅ Devrait fonctionner |

---

## Installation

1. Ouvrez `chrome://extensions/` ou `edge://extensions/`
2. Activez le **mode Développeur**
3. Cliquez sur **Charger le package décompressé** et sélectionnez le dossier du projet
4. Cliquez sur l'icône du minuteur dans votre barre d'outils

---

## Utilisation

1. **Cliquez sur l'icône de l'extension** pour ouvrir les paramètres
2. **Activez le widget** avec le commutateur dans l'en-tête (désactivé par défaut à la première installation)
3. **Sélectionnez le mode** — Chronomètre, Compte à rebours ou Pomodoro
4. **Le widget minuteur** apparaît sur la page — glissez-le où vous voulez
5. **▶ Démarrer / ⏸ Pause / ↺ Réinitialiser** — boutons de contrôle sur le widget
6. **⇄ Changer de mode** — naviguez entre les modes sur le widget
7. **🔒 Verrouiller** — empêche les déplacements accidentels
8. **— Minimiser** — réduit à la seule barre de titre
9. **🔔 Alertes bureau** — notification système quand le temps est écoulé (fonctionne même quand le navigateur est minimisé) ; l'icône de la barre d'outils affiche les minutes restantes

---

## Modes de minuteur

| Mode | Description |
|------|-------------|
| ⏱ **Chronomètre** | Comptage à partir de 00:00, sans limite de temps |
| ⏳ **Compte à rebours** | Réglez les minutes personnalisées (préréglages 10/25/30/60 ou personnalisé), compte à rebours jusqu'à 00:00 |
| 🍅 **Pomodoro** | Durées de travail/pause personnalisables (par défaut 25min/5min), continuation automatique optionnelle, sauter la pause |

---

## Confidentialité

- **storage** — Sauvegarde les paramètres, la position et l'historique en local
- **alarms** — Déclenche la fin du minuteur à l'heure exacte, même quand aucun onglet n'est visible
- **notifications** — Affiche la notification de bureau quand un minuteur se termine
- **Licence (optionnelle)** — Uniquement si vous activez une licence payante : une empreinte de l'appareil + des métadonnées du navigateur sont envoyées à `api.annmax1983.com` pour activer/valider la licence. Cela n'inclut jamais vos données de minuteur ni votre historique d'utilisation.
- Pas de requêtes réseau pour les fonctionnalités gratuites — tout le traitement se fait en local
- Les effets sonores sont générés dans le navigateur via le Web Audio API
- [Politique de confidentialité](privacy-policy.html)

---

## Avertissement relatif au droit d'auteur

Cette extension fournit un overlay de minuteur flottant local pour la commodité de l'utilisateur. Elle ne modifie, ne copie ni ne redistribue aucun contenu de site web.

---

## Avis sur le code source

> ⚠️ **Ce dépôt ne publie pas le code source.** Il contient uniquement la documentation d'utilisation, les notes de version et les ressources d'assistance. L'extension est distribuée exclusivement via le Chrome Web Store. Aucun package d'installation hors ligne ni code source destiné aux utilisateurs finaux n'est fourni.

---

## Licence

Copyright © 2026 RetroTime. Tous droits réservés.
