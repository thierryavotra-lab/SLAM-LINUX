# 🐧 SLAM Linux

Jeu de quiz  adapté pour apprendre les commandes Linux de manière ludique. Réalisé entièrement en script Bash, avec interface graphique Zenity, synthèse vocale, et mode multijoueur en réseau local WiFi.

---

## 🎮 Fonctionnalités

- **Mode Solo** — 3 niveaux progressifs (commandes de base, processus Linux, commandes avancées LPI), chronomètre de 15 secondes par question
- **Mode Multijoueur WiFi** — Duel entre deux joueurs sur le même réseau, chronomètre global de 200 secondes, 20 questions, signal de départ synchronisé (3, 2, 1, GO)
- **Mode Apprentissage** — Leçons détaillées sans chronomètre pour réviser avant de jouer
- **Synthèse vocale** — Les indices sont lus à voix haute (espeak-ng)

---
## 📦 Installation

### Téléchargement
Rendez-vous dans la section **[Releases](https://github.com/thierryavotra-lab/SLAM-LINUX/releases)** située sur la droite de cette page. 
Téléchargez le fichier `slam-linux_1.0_all.deb`.

### Installation (Ubuntu / Debian)
Une fois le fichier téléchargé, ouvrez un terminal dans le dossier de téléchargement et exécutez :

```bash
sudo apt install ./slam-linux_1.0_all.deb


Ou cherchez **SLAM Linux** dans le menu Applications (icône 🐧).

---





## 🗑️ Désinstaller

```bash
sudo apt remove slam-linux
```

---

## 📋 Prérequis

- Ubuntu 24.04 (ou dérivé compatible avec `apt`)
- `zenity` et `netcat-openbsd` (installés automatiquement)
- `espeak-ng` recommandé pour la voix (installé automatiquement si possible)



