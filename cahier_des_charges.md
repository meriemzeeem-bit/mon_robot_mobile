# Cahier des charges — Robot mobile ROS 2

## 1. Présentation du projet

Le projet consiste à modéliser et visualiser un robot mobile omnidirectionnel à quatre roues Mecanum en utilisant ROS 2 Jazzy. La description du robot sera réalisée avec URDF/Xacro, puis affichée en trois dimensions dans RViz. Le modèle ROSMASTER X3 de Yahboom servira de référence.

## 2. Problématique

Comment décrire et visualiser un robot mobile dans ROS 2 en représentant correctement sa structure mécanique, ses articulations et ses capteurs ?

## 3. Objectifs

- Créer un package ROS 2 de description du robot.
- Décrire sa structure mécanique avec URDF/Xacro.
- Intégrer les modèles 3D des composants.
- Représenter les quatre roues Mecanum.
- Décrire les capteurs : caméra RGB-D, LiDAR et IMU.
- Visualiser le robot dans RViz.
- Vérifier les articulations et les repères de coordonnées.

## 4. Architecture du système

- Châssis et roues Mecanum.
- Modèles 3D des composants mécaniques.
- Description URDF/Xacro.
- Description des capteurs.
- Outils ROS 2 et RViz.

## 5. Outils utilisés

- Ubuntu 24.04 LTS.
- ROS 2 Jazzy.
- URDF/Xacro.
- RViz.
- Visual Studio Code.
- GitHub.

## 6. Fonctionnalités attendues

- Charger la description du robot.
- Afficher le modèle 3D dans RViz.
- Visualiser les roues, le châssis et les capteurs.
- Afficher les repères TF.
- Tester les articulations avec les outils ROS 2 adaptés.

## 7. Résultats attendus

Obtenir un modèle robotique correctement décrit et visualisé dans RViz.

## 8. Limites du projet

Cette première étape porte sur la description et la visualisation du robot. Le déplacement physique, la simulation Gazebo et la navigation autonome nécessitent des développements supplémentaires.

