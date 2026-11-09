# Jeu d'Aventure Textuel - TP Web HTML & CSS

## Installation

- **1. Installer Visual Studio Code** (ou un autre éditeur de texte)
    [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
- **2. Installer GIT**
    [https://git-scm.com/](https://git-scm.com/)
- **3. Cloner le repository**
    Ouvrez votre terminal et exécutez la commande suivante :
    ```bash
    git clone https://github.com/kost84/Racheter-Lioris-TP-Web.git
    ```

## Description du projet

Ce projet est un jeu d'aventure textuel où le héros avance de page en page en faisant des choix. Chaque décision mène à une nouvelle page créant ainsi une histoire. 

Il a été réalisé dans le cadre du TP "Initiation Web HTML & CSS". L'objectif  principal est de mettre en application les bases du HTML et du CSS de structurer .

## Utilisation

Le projet étant un site web  il ne nécessite aucun serveur ou installation complexe pour fonctionner. 

1. Ouvrez le dossier cloné sur votre ordinateur.
2. installer le pluggin Local Serveur .
3. Lisez la description de la scène et cliquez sur les boutons de choix pour progresser dans l'aventure.

## Fonctionnalités et Contraintes respectées

Le jeu a été développé en respectant les contraintes suivantes :

1. **Navigation et Ramification**
   - Un minimum de **10 pages HTML** interconnectées constituant les différentes scènes de l'histoire.
   - Les choix du joueur impactent directement le déroulement de l'aventure.

2. **Design et Immersion**
   - **scène complet :** Chaque page contient un titre une image de fond d'ambiance un paragraphe narratif et des boutons de choix.
   - **Boutons personnalisés :** Les boutons de navigation sont stylisés en CSS.
   - **Icônes :** Intégration d'icônes sur certains boutons pour illustrer les actions. 
   - HTML et CSS propres, structurés et sémantiques.

3. **Documentation**
   - Présence de l'arbre de navigation au format PDF cartographiant tous les embranchements possibles.

## Structure des fichiers

Le code est divisé en plusieurs dossiers pour une meilleure lisibilité et modularité, conformément aux consignes :

```text
.
├── index.html                # Page d'accueil point de départ de l'aventure
├── style.css                 # Feuille de style globale partagée par toutes les pages
├── arbre-navigation.pdf      # Schéma de l'arbre de navigation 
├── README.md                 # Fichier de présentation du projet
├── pages/                    # Dossier contenant toutes les scènes du jeu
│   ├── scene01.html
│   ├── scene02.html
│   └── ... (scènes 03 à 10+)
└── assets/                   # Dossier contenant les ressources graphiques 
    ├── backgrounds/          # Images de fond pour les scènes
    ├── icons/                # Icônes locales si non gérées par CDN
    └── sounds/               #  Sons et ambiances audio
```

>  **Avertissement :** Les images et illustrations (backgrounds) utilisées pour illustrer les scènes de ce projet ainsi que corrigée le README ont été générées par l'intelligence artificielle .

## Auteur

**Lioris Racheter**  
