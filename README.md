# CoLANTube

> ⚠️ Projet en cours de conception – version 0.x  
> CoLANTube n’est pas encore utilisable en production.

## 📖 Présentation
CoLANTube est un projet de **jukebox collaboratif en réseau local (LAN)** destiné à des petites communautés ou des environnements professionnels.

Les utilisateurs peuvent proposer des titres musicaux depuis **YouTube** (et à terme Jamendo) via une interface web simple, pensée pour des personnes **non familières avec l’informatique**.

Le projet vise à fonctionner **sans service cloud, sans compte utilisateur**, et avec une **installation 100 % portable**, y compris sur des machines anciennes.

## 🧭 Philosophie du projet
- Usage **local uniquement** (LAN)
- Simplicité d’utilisation avant tout
- Respect des contraintes humaines (quotas, horaires, équité)
- Architecture modulaire et évolutive
- Portabilité maximale (Windows prioritaire)

## 🛠️ Fonctionnalités prévues
*(Certaines fonctionnalités sont en cours de conception et non encore implémentées)*

- 🎵 Ajout de titres depuis YouTube (recherche ou lien direct)
- ⏳ Gestion de quotas par utilisateur pour éviter les abus
- 🎧 Lecture audio via un moteur configurable (MPD, VLC ou autre)
- 🌐 Interface web simple et responsive
- 🧩 Architecture client / serveur avec échange P2P local
- ⏬ Mise en cache temporaire des fichiers audio
- 📊 Statistiques et easter-eggs communautaires
- 🔑 Interface d’administration protégée
- 🕒 Gestion stricte des horaires de fonctionnement

## 🚧 État actuel
- ✅ Conception et cahier des charges en cours
- ✅ Mise en place du dépôt et de l’architecture initiale
- ⏳ Développement non entamé

## 🎯 Objectifs
- Offrir une expérience fluide et équitable pour une playlist musicale collaborative en LAN
- Fonctionner sur du matériel ancien et hétérogène
- Rester compréhensible et maintenable dans le temps

## 📌 Licence
À définir.
=======
## 📖 Présentation  
Ce projet est une plateforme de playlist collaborative en réseau local.  
Les utilisateurs peuvent ajouter des titres depuis YouTube ou Jamendo et les écouter ensemble.  
D'autres fonctionnalités sont disponibles, comme le téléchargement temporaire de MP3 et la création de sonneries.  

## 🛠️ Fonctionnalités  
- 🎵 Ajout de titres YouTube/Jamendo à une playlist partagée  
- ⏳ Gestion des quotas pour éviter les abus  
- 🎧 Lecture via un lecteur MPD, VLC  ou HTML5 (selon configuration)
- ⏬ Téléchargement temporaire des MP3 (60 min par défaut)  
- 🔊 Création de sonneries personnalisées  
- 📊 Statistiques et classement des utilisateurs (Easter-eggs 🎉)  
- 🔑 Interface d’administration protégée  

## 🚀 Installation  
### 1️⃣ Prérequis  
- Python 3  
- `yt-dlp` (fourni en version portable)  

### 2️⃣ Installation  
Clonez le dépôt et installez les dépendances :  
```sh
git clone git@github.com:rickeymandraque/CoLANTube.git
cd mon-projet
pip install -r requirements.txt
```
### 3️⃣ Lancer le serveur
```sh
python src/main.py
```
L'interface est accessible sur `http://localhost:5000`.

### 🎯 Objectifs
- 📌 Offrir une expérience simple et fluide pour une playlist collaborative en LAN.
- 📌 Rendre le projet facilement portable et auto-hébergé.