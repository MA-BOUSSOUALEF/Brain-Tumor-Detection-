# MRI Tumor Detection System

Le **MRI Tumor Detection System** est une application web permettant de détecter la présence de tumeurs cérébrales à partir d'images IRM (Imagerie par Résonance Magnétique). Ce système utilise un modèle de machine learning pré-entraîné basé sur **TensorFlow** et **Keras** pour effectuer la classification des images.

## Fonctionnalités

- **Upload d'images IRM** : Les utilisateurs peuvent télécharger une image IRM via une interface web.
- **Prédiction automatique** : Le modèle analyse l'image et prédit si une tumeur est présente et, si oui, quel type de tumeur il s'agit.
- **Affichage des résultats** : L'application affiche le type de tumeur détecté, ainsi que le pourcentage de confiance de la prédiction.
- **Interface utilisateur simple** : Une interface web intuitive permet de charger une image et de visualiser immédiatement les résultats.

## Types de tumeurs détectés

Le modèle est capable de détecter les types de tumeurs cérébrales suivants :

- **Gliome** : Tumeur qui se développe dans les cellules gliales du cerveau.
- **Méningiome** : Tumeur qui se développe dans les membranes qui entourent le cerveau et la moelle épinière.
- **Pituitaire** : Tumeur de la glande pituitaire, responsable de la production d'hormones.
- **Pas de tumeur** : Prédiction indiquant qu'il n'y a pas de tumeur présente dans l'image IRM.

## Objectif

Le but de ce projet est de démontrer l'application des techniques d'intelligence artificielle et de deep learning pour l'analyse médicale, notamment en ce qui concerne l'analyse d'images médicales. Le modèle utilise un réseau de neurones convolutifs (CNN) pour traiter les images IRM et faire des prédictions sur la présence et le type de tumeur.

## Technologies utilisées

- **Flask** : Framework web pour la création de l'application.
- **TensorFlow / Keras** : Bibliothèques pour la création et l’entraînement du modèle de deep learning.
- **HTML/CSS** : Technologies utilisées pour l'interface utilisateur.
- **Python** : Langage de programmation utilisé pour le développement de l'application.

## Limites du projet

Ce projet est à des fins éducatives et de démonstration uniquement. Il ne doit pas être utilisé dans un cadre clinique réel sans validation médicale. Le modèle a été entraîné sur un jeu de données spécifique et ne peut garantir des résultats parfaits pour toutes les images IRM.

## Auteurs

**Amine**  
Contact : amine@example.com
