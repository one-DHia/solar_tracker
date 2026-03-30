# Optimisation Photovoltaïque : Simulation de Tracker Solaire avec Régulateur PID

## 📖 Description du Projet
Ce projet consiste en une simulation en Python comparant l'efficacité énergétique d'une installation de panneaux solaires statiques face à un système de suivi dynamique (Tracker Solaire). Le suivi de l'élévation solaire est modélisé et contrôlé par un **algorithme de régulation PID (Proportionnel-Intégral-Dérivé)**.

L'objectif est de démontrer algorithmiquement le gain de rendement d'un système asservi face aux variations météorologiques (irradiance fluctuante) et à la course du soleil.

## 🛠️ Stack Technique
* **Langage** : Python 3
* **Librairies** : 
  * `NumPy` : Modélisation mathématique (trigonométrie de l'élévation, génération de bruit stochastique pour la météo).
  * `Matplotlib` : Visualisation des données et comparaison de l'aire sous la courbe (calcul de l'énergie totale).

## 📊 Résultats
L'implémentation du contrôleur PID permet au tracker de réduire l'erreur d'alignement proche de 0 en temps réel. La simulation sur une journée type de 12 heures démontre **un gain de production énergétique supérieur à 35%** par rapport à une installation fixe standard (inclinée à 30°).
