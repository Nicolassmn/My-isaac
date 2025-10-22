<h1 align="center">🩸 Binding of Isaac RPG — Remake amateur</h1>

<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/<TON_USER>/binding-of-isaac-rpg/build.yml?branch=main&label=Build&logo=github&color=blue" alt="build status" />
  <img src="https://img.shields.io/github/license/<TON_USER>/binding-of-isaac-rpg?color=red" alt="license" />
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="C Language" />
</p>

---

## 📑 Table of Contents / Sommaire

- [🇬🇧 English](#english)
- [🇫🇷 Français](#français)

---

## 🇬🇧 English

### 🧠 Presentation

**Binding of Isaac RPG Remake** is a personal project where I wanted to recreate a small RPG inspired by *The Binding of Isaac*.  
⚠️ Warning: visually, everything was **handmade** with love… technically, it’s mostly an **experimental draft** to test my skills in C, sprite handling, collisions, and game logic.  

So it’s not a finished game, it’s a **“tech & art DIY project”** 😅

---

### 🎬 Game Demo

<div align="center">
  <img src="assets/demo.gif" alt="Game Demo" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" />
</div>

---

### ⚙️ Main Features

✅ Smooth character movement  
✅ Collision and wall handling  
✅ Basic enemy management  
✅ Projectiles and attacks  
✅ Rudimentary interface and HUD  
✅ Health and pickups management  
✅ Simple enemy AI  
✅ Level management and room spawning  

---

### 🛠️ Build & Run

<p align="center">

| Step | Command | Description |
|------|---------|-------------|
| 🔹 Compile the project | <code>make</code> | Compiles all source files and generates `myrpg` executable |
| 🧹 Clean object files | <code>make clean</code> | Removes temporary files (`*.o`, `*~`) |
| ❌ Remove everything | <code>make fclean</code> | Removes object files and executable |
| 🔄 Recompile | <code>make re</code> | Cleans then compiles the project again |
| ▶️ Run the game | <code>./myrpg</code> | Launches the RPG |

</p>

### Project Structure
```
.
├── assets
├── include
├── save
└── src
```
=====
---

### ⬇️ Download (precompiled version)

<p align="center">
🔹 **Latest ready-to-use version** :<br>
[👉 Download myrpg (release latest)](https://github.com/Nicolassmn/My-shell/releases/download/latest/myrpg)<br>
*(precompiled executable, ready to run!)*
</p>

<p align="center">
Or clone the project from GitHub :<br>
<code>git clone git@github.com:Nicolassmn/My-Shell.git</code>
</p>

---

### 🧪 CI/CD Workflow

Each push on the `main` branch:

<p align="center">
- 🔨 Automatically compiles the project <br>
- 🚀 Publishes the binary to the “latest” release <br>
*(see <code>.github/workflows/build.yml</code>)*
</p>

---

## 🇫🇷 Français

### 🧠 Présentation

**Binding of Isaac RPG Remake** est un projet personnel où j’ai voulu recréer un petit RPG inspiré de *The Binding of Isaac*.  
⚠️ Avertissement : visuellement, tout a été fait **à la main** et avec amour… mais techniquement, c’est surtout un **brouillon expérimental** pour tester mes compétences en C, gestion de sprites, collisions, et logique de jeu.  

Bref, ce n’est pas un jeu fini, c’est un **projet “technique et artistique bricolé”** 😅

---

### 🎬 Démo du jeu

<div align="center">
  <img src="assets/demo.gif" alt="Démonstration du RPG" style="max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" />
</div>

---

### ⚙️ Fonctionnalités principales

✅ Déplacement fluide du personnage  
✅ Gestion des collisions et murs  
✅ Gestion des ennemis basiques  
✅ Projectiles et attaques  
✅ Interface rudimentaire et HUD  
✅ Gestion de la santé et des pickups  
✅ Petite IA pour ennemis (basique mais fonctionnelle)  
✅ Gestion de niveaux et spawn des rooms  

---

### 🛠️ Compilation & Exécution

<p align="center">

| Étape | Commande | Description |
|-------|----------|-------------|
| 🔹 Compiler le projet | <code>make</code> | Compile tous les fichiers source et génère l’exécutable `myrpg` |
| 🧹 Nettoyer les fichiers objets | <code>make clean</code> | Supprime les fichiers temporaires (`*.o`, `*~`) |
| ❌ Supprimer tout | <code>make fclean</code> | Supprime les fichiers objets et l’exécutable |
| 🔄 Recompiler | <code>make re</code> | Nettoie puis compile à nouveau le projet |
| ▶️ Exécuter le jeu | <code>./myrpg</code> | Lance le jeu |

</p>

### Structure du projet
```
.
├── assets
├── include
├── save
└── src
```
=======
---

### ⬇️ Téléchargement (version compilée)

<p align="center">
🔹 **Dernière version prête à l’emploi** :<br>
[👉 Télécharger myrpg (release latest)](https://github.com/Nicolassmn/My-Shell/releases/download/latest/myrpg)<br>
=======
[👉 Télécharger mysh (release latest)](https://github.com/Nicolassmn/My-shell/releases/download/latest/myrpg)<br>
>>>>>>> fbbf7bdf01ef253c961962de5640c3d3d34009d3
*(exécutable déjà compilé, prêt à être lancé !)*
</p>

<p align="center">
Ou cloner le projet depuis GitHub :<br>
<code>git clone git@github.com:Nicolassmn/My-Shell.git</code>
</p>

---

### 🧪 Workflow CI/CD

Chaque push sur la branche `main` :

<p align="center">
- 🔨 Compile automatiquement le projet <br>
- 🚀 Publie le binaire dans la release “latest” <br>
*(voir <code>.github/workflows/build.yml</code>)*
</p>
