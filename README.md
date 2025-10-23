<h1 align="center">🩸 Binding of Isaac RPG — Remake amateur</h1>

<p align="center">
  <a href="#EN">🇬🇧 English</a> • <a href="#FR">🇫🇷 Français</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/Nicolassmn/my-isaac/build.yml?branch=main&label=Build&logo=github&color=blue" alt="build status" />
  <img src="https://img.shields.io/github/license/Nicolassmn/my-isaac?color=red" alt="license" />
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="C Language" />
</p>

---

### 🎬 Demo

<div align="center">
  <img src="assets/demo.gif" alt="Game Demo" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" />
</div>

---

### 🛠️ Build & Run

| Étape / Step                                                 | Commande / Command       | Description                                                                                                                                             |
| ------------------------------------------------------------ | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🔹 **Compiler le projet** / **Compile the project**          | <code>make</code>        | Compile tous les fichiers sources et génère l’exécutable <code>myrpg</code> / Compiles all source files and generates the <code>myrpg</code> executable |
| 🧹 **Nettoyer les fichiers objets** / **Clean object files** | <code>make clean</code>  | Supprime les fichiers temporaires (<code>*.o</code>) / Removes temporary files (<code>*.o</code>)                                                       |
| ❌ **Tout supprimer** / **Remove everything**                 | <code>make fclean</code> | Supprime les fichiers objets et l’exécutable / Removes object files and executable                                                                      |
| 🔄 **Recompiler** / **Recompile**                            | <code>make re</code>     | Nettoie puis recompile le projet / Cleans then recompiles the project                                                                                   |
| ▶️ **Lancer le jeu** / **Run the game**                      | <code>./myrpg</code>     | Lance le RPG / Launches the RPG                                                                                                                         |


---

### Project Structure
```
.
├── assets
├── include
├── save
└── src
```

---

## 🇬🇧 English <a id="EN"></a>

### 🧠 Overview

**Binding of Isaac RPG Remake** - is a small *2D RPG prototype* inspired by The Binding of Isaac, fully coded in *C*.
This project was mainly a *technical challenge*, built to practice *sprite management, collisions, AI, and basic game logic*.

---

### ⚔️ Gameplay

  🔹 Move around freely in a room-based map  
  🔹 Face enemies with simple attacks and projectiles  
  🔹 Pick up hearts and items to restore HP  
  🔹 Progress through rooms and survive as long as possible  

---

### ✨ Features

  🔹 Smooth character movement  
  🔹 Collision and wall handling  
  🔹 Basic enemy management  
  🔹 Projectiles and attacks  
  🔹 Rudimentary interface and HUD  
  🔹 Health and pickups management  
  🔹 Simple enemy AI  
  🔹 Level management and room spawning  

---

### ⬇️ Download (precompiled version)

<p align="center"> 🔹 <strong>Latest ready-to-use version:</strong><br> <a href="https://github.com/Nicolassmn/My-isaac/releases/download/latest/myrpg">👉 Download myrpg (latest release)</a><br> <em>Precompiled executable — ready to play!</em> </p> <p align="center"> Or clone the repository:<br> <code>git clone git@github.com:Nicolassmn/My-isaac.git</code> </p>

---

### 🧪 CI/CD Workflow

Each push on the <code>main</code> branch:

<p align="center"> 🔨 Automatically compiles the project <br> 🚀 Publishes the binary to the “latest” release <br> 🧩 Defined in <code>.github/workflows/build.yml</code> </p>

---

## 🇫🇷 Français

### 🧠 Présentation

**Binding of Isaac RPG Remake** est un petit *prototype de RPG 2D* inspiré de The Binding of Isaac, entièrement codé en *C*.
Ce projet était avant tout un *défi technique*, conçu pour pratiquer la *gestion des sprites*, des *collisions*, de l’*IA* et de la *logique de jeu de base*.

---

### ⚔️ Principe du jeu

🔹 Déplacez-vous librement entre les salles  
🔹 Affrontez des ennemis avec vos attaques et projectiles  
🔹 Récupérez des cœurs et objets pour restaurer vos points de vie  
🔹 Progressez de salle en salle et survivez le plus longtemps possible  

---

### ✨ Fonctionnalités

🔹 Déplacement fluide du personnage  
🔹 Gestion des collisions et murs  
🔹 Système d’ennemis basique  
🔹 Projectiles et attaques  
🔹 Interface rudimentaire et HUD  
🔹 Gestion de la santé et des pickups  
🔹 Petite IA ennemie  
🔹 Gestion des niveaux et génération des salles  

---

### ⬇️ Téléchargement (version compilée)

<p align="center"> 🔹 <strong>Dernière version prête à l’emploi :</strong><br> <a href="https://github.com/Nicolassmn/My-isaac/releases/download/latest/myrpg">👉 Télécharger myrpg (release latest)</a><br> <em>Exécutable précompilé — prêt à jouer !</em> </p> <p align="center"> Ou cloner le dépôt :<br> <code>git clone git@github.com:Nicolassmn/My-isaac.git</code> </p>

---

### 🧪 Workflow CI/CD

Chaque push sur la branche <code>main</code> :

<p align="center"> 🔨 Compile automatiquement le projet <br> 🚀 Publie le binaire dans la release “latest” <br> 🧩 Défini dans <code>.github/workflows/build.yml</code> </p>

---
