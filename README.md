# 🎮 CardYard  

> 🧩 Projet académique réalisé à **CY Tech** (année universitaire **2024–2025**)   
> 🧠 **Objectif :** créer un jeu de cartes multijoueur en C, mettant en pratique la logique algorithmique, la gestion mémoire et la programmation modulaire.  

---

## 💼 Pour les recruteurs
- **Langage :** C (standard C99)  
- **Outils :** GCC, Makefile, Git/GitHub  
- **Compétences clés :** algorithmique, structures de données, modularité, logique de jeu, travail en équipe  
- **Rôle personnel :** coordination du groupe, développement du module d’affichage, mise en place du Makefile et intégration finale  

---

## 🧾 Présentation du projet

CardYard est un **jeu de cartes multijoueur** en ligne de commande développé en **langage C**.  
Il met en œuvre la **pioche, la défausse, l’échange de cartes et le classement final automatique** des joueurs selon leurs scores.

---

## 🔧 Compilation et exécution

### Compiler le projet
```bash
make
Exécuter le jeu
bash
Copier le code
./cardyard
🧹 Nettoyage
Supprimer les fichiers objets (.o)
bash
Copier le code
make clean
Supprimer également l’exécutable
bash
Copier le code
make mrproper
🕹 Fonctionnalités
Jusqu'à 8 joueurs

Distribution aléatoire ou personnalisée des cartes

3 variantes pour générer la pioche :

VALUE_FILE : lecture depuis un fichier texte (valeurs.txt)

VALUE_USER : saisie manuelle de la plage de valeurs

Par défaut : jeu classique avec les cartes de -2 à 12

Sauvegarde et rechargement de partie (sauvegarde.txt)

Affichage stylisé avec codes couleurs ANSI

Classement final automatique des joueurs par score

🗂 Structure des fichiers
main.c — logique principale du jeu

cartes.h — définitions des structures Carte, Joueur, Pioche

initialisation.c — génération et distribution des cartes

affichage.c/h — affichage du plateau et des scores

jeu.c — logique avancée et affichage ASCII

Makefile — automatisation de la compilation

💾 Sauvegarde
Une sauvegarde de partie est enregistrée automatiquement dans :

Copier le code
sauvegarde.txt
Elle est créée lorsque le joueur choisit l’option "Sauvegarder et quitter".

👥 Équipe de développement
Taissir Rguig — coordination, affichage, intégration du projet

Shems Boudjebina — structures de données et Makefile

Antoine Boudon-Guillot — logique de pioche et gestion de la sauvegarde

🧰 Outils et technologies
Langage : C

Compilateur : GCC

IDE / Éditeurs : Visual Studio Code, CLion, Terminal Linux

Gestion de version : Git et GitHub

🎯 Objectifs pédagogiques
Projet réalisé dans le cadre du module Informatique en C, à CY Tech, année universitaire 2024–2025.
Ce travail a permis de développer :

la rigueur algorithmique

la gestion de la mémoire

la programmation modulaire

le travail collaboratif

la rédaction technique claire

---
