# djermounethanina.github.io
Xiangqi Modifié — Projet de Jeu d’Échecs Chinois
Description du projet

Ce projet consiste à développer une application du jeu d’échecs chinois (Xiangqi) avec un plateau modifié pour l’expérimentation algorithmique et pédagogique.

Le jeu est conçu autour d’une architecture séparant le moteur de jeu, la logique des règles et l’interface graphique interactive.

 --Objectifs principaux

Visualiser un plateau de jeu 11 × 11 cases incluant :

9 colonnes jouables

2 colonnes neutres non jouables servant de murs symboliques

1 ligne représentant la rivière stratégique

Implémenter les règles spécifiques des pièces du Xiangqi modifié

Garantir la validation automatique des coups légaux

Proposer un mode :

Joueur vs Bot

Deux joueurs sur la même interface

 --Pièces du jeu

Le jeu contient 16 pièces par joueur :

1 Général

2 Conseillers

2 Éléphants

2 Chevaux

2 Chariots

2 Canons

5 Soldats

Chaque pièce possède des règles de déplacement spécifiques.

 --Règles principales

Impossible de laisser son Général en position capturable.

Les déplacements doivent respecter les contraintes du plateau et des pièces.

Les colonnes neutres sont interdites pour l’arrêt des pièces.

Les captures doivent suivre strictement les règles de déplacement.

Les deux Généraux ne peuvent jamais être alignés sans pièce intermédiaire.

 --Fonctionnalités de l’application

Affichage graphique du plateau de jeu modifié

Sélection des pièces par clic et affichage des mouvements légaux

Déplacement et capture uniquement si le coup est valide

Mode joueur contre bot

Mode deux joueurs avec orientation dynamique du plateau

Gestion automatique des fins de partie

 --Moteur de jeu

Le moteur de jeu gère :

La validation des coups

Les règles de déplacement

La détection d’échec

La détection de fin de partie

 --Auteurs

Ramdane Ketfi

Mamadou Saliou Sow

Djermoune Thanina
