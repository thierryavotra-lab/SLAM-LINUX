# 🐧 SLAM Linux

Jeu de quiz inspiré de l'émission **SLAM** (France Télévisions), adapté pour apprendre les commandes Linux de manière ludique. Réalisé entièrement en script Bash, avec interface graphique Zenity, synthèse vocale, et mode multijoueur en réseau local WiFi.

---

## 🎮 Fonctionnalités

- **Mode Solo** — 3 niveaux progressifs (commandes de base, processus Linux, commandes avancées LPI), chronomètre de 15 secondes par question
- **Mode Multijoueur WiFi** — Duel entre deux joueurs sur le même réseau, chronomètre global de 200 secondes, 20 questions, signal de départ synchronisé (3, 2, 1, GO)
- **Mode Apprentissage** — Leçons détaillées sans chronomètre pour réviser avant de jouer
- **Synthèse vocale** — Les indices sont lus à voix haute (espeak-ng)

---

## 📦 Installation sur Ubuntu 24.04

### Étape 1 — Télécharger le paquet

```bash
wget https://github.com/VOTRE_NOM/slam-linux/raw/main/slam-linux_1.1_all.deb
```

### Étape 2 — Installer

```bash
sudo apt install ./slam-linux_1.1_all.deb
```

`apt` installe automatiquement les dépendances nécessaires (`zenity`, `netcat`).

### Étape 3 — Lancer le jeu

```bash
slam-linux
```

Ou cherchez **SLAM Linux** dans le menu Applications (icône 🐧).

---

## 🔄 Mettre à jour vers une nouvelle version

```bash
wget https://github.com/VOTRE_NOM/slam-linux/raw/main/slam-linux_1.1_all.deb
sudo apt install ./slam-linux_1.1_all.deb
```

`apt` remplace automatiquement l'ancienne version si elle est déjà installée.

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

---

## 📜 Historique des versions

| Version | Changements |
|---|---|
| 1.1 | Mode multijoueur revu : chrono global 200s, 20 questions, signal de départ synchronisé |
| 1.0 | Version initiale — 3 niveaux solo, multijoueur WiFi, mode apprentissage |
