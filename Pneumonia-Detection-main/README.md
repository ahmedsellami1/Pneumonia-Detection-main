# 🩺 Pneumonia Detection System

Ce dépôt contient un projet complet de Deep Learning appliqué à l'imagerie médicale, ayant pour objectif de détecter la pneumonie à partir de radiographies thoraciques. Le projet est structuré autour de deux notebooks principaux : l'entraînement du modèle et l'évaluation/test.

---

## 📂 Structure du Dépôt

Le projet s'articule autour des deux fichiers suivants :

| Fichier | Description |
| :--- | :--- |
| [`pnemonie.ipynb`](./pnemonie.ipynb)[cite: 4] | Notebook dédié au prétraitement des données, à l'augmentation des images et à l'entraînement du modèle de classification par réseau de neurones convolutifs (CNN). |
| [`test_data.ipynb`](./test_data.ipynb)[cite: 4] | Notebook dédié aux tests, à l'évaluation des performances sur des données invisibles et aux prédictions unitaires. |

---

## 🚀 Fonctionnalités Principales

- **Prétraitement d'images médicales** : Redimensionnement, normalisation et conversion pour uniformiser le dataset.
- **Augmentation des données** : Application de techniques de transformation (rotation, zoom, cisaillement) pour rendre le modèle plus robuste et éviter le surapprentissage.
- **Modélisation CNN** : Architecture séquentielle conçue pour extraire les caractéristiques pertinentes des radiographies thoraciques.
- **Évaluation rigoureuse** : Scripts de test séparés pour valider la capacité de généralisation du modèle.

---

## 🛠️ Technologies & Bibliothèques Utilisées

- **Python** (Langage principal)
- **TensorFlow / Keras** (Construction et entraînement du modèle de Deep Learning)
- **OpenCV / Pillow** (Traitement et manipulation d'images)
- **NumPy / Pandas** (Manipulation et analyse des données)
- **Matplotlib / Seaborn** (Visualisation des résultats et des courbes d'apprentissage)

---

