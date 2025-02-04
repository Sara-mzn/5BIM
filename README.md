# Détection d'Objets en Temps Réel avec YOLOv5 et OpenCV

## Description
Ce projet utilise le modèle pré-entraîné YOLOv5 et la bibliothèque OpenCV pour détecter des objets en temps réel à partir du flux vidéo d'une webcam. Il identifie et encadre les objets reconnus, tout en affichant le nom et le pourcentage de confiance pour chaque détection. Le projet est écrit en Python et utilise des fonctions asynchrones pour améliorer les performances de traitement.

## Fonctionnalités
- Détecter divers objets dans un flux vidéo en temps réel.
- Encadrer et étiqueter les objets détectés avec une précision de confiance.
- Filtrer et colorer différemment les cadres en fonction du type d'objet (ordinateurs portables et souris).

## Prérequis
- Python-3.11.9
- Webcam fonctionnelle connectée à votre ordinateur.

## Dépendances
- opencv-python-headless
- numpy
- torch
- aiohttp (pour de futures extensions nécessitant des requêtes asynchrones)
- python-dotenv (pour gérer les variables d'environnement)

## Clonnage du projet

1. Clonez le dépôt :


## Installation

2. Installer les dépendences :
    pip install -r requirements.txt

## Demarrage de la detction 
3. Lancer le main
    python main.py

## Liens
- Repository GitHub : https://github.com/Sara-mzn/5BIM
#   5 B I M  
 