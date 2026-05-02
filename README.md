# Classification des activités humaines à partir de données de capteurs multimodaux

## Aperçu
Ce projet vise à classifier les activités humaines à l'aide de données biométriques multimodales collectées par divers capteurs tels que l'EMG, l'IMU et l'IPS.

L'objectif est de concevoir et d'évaluer une architecture de traitement de données capable de gérer des données de capteurs complexes afin de prédire avec précision les activités physiques.

---

## Objectif
Développer un système de classification robuste permettant d'identifier différents types d'exercices physiques à partir de données de capteurs.

L'ensemble de données comprend des mouvements catégorisés comme suit :

- Arrière
- Avant
- Demi-squat
- Immobile

---
## Méthodologie
- Prétraitement et synchronisation des signaux multimodaux
- Extraction de caractéristiques à partir des capteurs EMG, IMU et IPS
- Conception d'architectures d'apprentissage profond (CNN + LSTM)
- Implémentation de deux approches :

- Architecture unifiée (toutes les modalités combinées)

- Architecture multimodale (traitement séparé + fusion)
- Entraînement et évaluation des performances des modèles
- Comparaison des différentes architectures

---

## Outils et technologies
- Python
- Apprentissage profond (CNN, LSTM)
- Traitement du signal
- Analyse de données multimodales

---

## Résultats
Les modèles classent avec succès les activités humaines à partir des données des capteurs, démontrant l'efficacité de la combinaison des caractéristiques temporelles (LSTM) et spatiales (CNN).

La comparaison met en évidence les différences de performances entre les architectures unifiée et multimodale.

---

## Cas d'utilisation

Ce type de solution peut être appliqué dans les domaines suivants :

- Analyse des performances sportives

- Systèmes de surveillance de la santé

- Réadaptation et physiothérapie

- Systèmes de reconnaissance de l'activité humaine

---
