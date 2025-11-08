# 🎮 CardYard  

**CardYard** est un **jeu de cartes multijoueur** développé en **langage C** dans le cadre du module d’informatique à **CY Tech**.  
Le projet met en œuvre la **logique de pioche, de défausse, d’échange de cartes**, et un **classement final automatique** des joueurs selon leurs scores.

---

## ⚙️ Fonctionnalités principales
- Jusqu’à **8 joueurs**
- **Distribution aléatoire ou personnalisée** des cartes
- **3 modes de génération de la pioche** :
  - **VALUE_FILE** : lecture depuis un fichier texte (`valeurs.txt`)
  - **VALUE_USER** : saisie manuelle des valeurs et quantités
  - **Mode par défaut** : jeu classique avec des valeurs de -2 à 12
- **Sauvegarde et rechargement** automatique des parties (`sauvegarde.txt`)
- **Affichage stylisé** des cartes via **codes couleurs ANSI**
- **Classement final automatique** selon les scores

---

## 🧠 Compétences et concepts techniques
- Programmation en **langage C (standard C99)**
- Utilisation avancée de :
  - **Structures**, **pointeurs**, **tableaux 2D**, **fonctions**
  - **Boucles imbriquées** et **conditions**
  - **Gestion de fichiers (I/O)** avec `fopen`, `fprintf`, `fscanf`
- Conception d’un **Makefile** pour automatiser la compilation
- Application des principes de **modularité du code** (plusieurs fichiers `.c` / `.h`)
- Gestion de projet collaboratif via **Git et GitHub**

---

## 📂 Structure du projet
├── main.c # Logique principale du jeu
├── affichage.c/h # Affichage graphique (couleurs ANSI, scores, plateau)
├── cartes.h # Structures des cartes, joueurs et pioche
├── initialisation.c # Génération et distribution des cartes
├── jeu.c # Fonctions d'affichage et logique du jeu
├── valeurs.txt # Fichier des valeurs pour la pioche
├── Makefile # Compilation automatisée du projet
└── README.md # Documentation du projet

yaml
Copier le code

---

## 👥 Équipe de développement
- **Taissir Rguig** — coordination de l’équipe, logique du jeu, fonctions d’affichage  
- **Shems Boudjebina** — conception du Makefile, structures de données, intégration du code  
- **Antoine Boudon-Guillot** — logique de pioche et gestion de la sauvegarde  

---

## 🧰 Outils et technologies
- **Langage :** C  
- **Compilateur :** GCC  
- **IDE / éditeurs :** Visual Studio Code, CLion, Terminal Linux  
- **Gestion de version :** Git et GitHub  

---

## 🎯 Objectifs pédagogiques
Projet académique réalisé dans le cadre du module **Informatique en C**, année universitaire **2024–2025** à **CY Tech**.  
Il a permis de développer les compétences suivantes :
- Rigueur algorithmique  
- Gestion de la mémoire  
- Travail collaboratif  
- Documentation technique claire  

---

## 🇬🇧 English Summary
**CardYard** is a **multiplayer card game** coded in **C language**, featuring draw, discard, and scoring logic.  
It includes **file I/O**, **ANSI graphic display**, and **automated compilation** via Makefile.  
Team project — academic work at CY Tech, academic year **2024–2025**.
