# CoLANTube

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
