# Prédiction de la Taille de Vêtements avec le Machine Learning

Ce projet utilise un modèle de machine learning pour prédire la taille de vêtements en fonction du poids, de l'âge et de la hauteur d'une personne. L'application est développée avec Streamlit et est déployée via ngrok.

## Contenu du Projet

- `sizes.csv` : Jeu de données contenant les tailles de vêtements et leurs caractéristiques (poids, âge, hauteur).
- `notebook.ipynb` : Notebook Jupyter avec le code d'entraînement du modèle et les explications détaillées.

## Prérequis

Vous aurez besoin d'un compte Google pour utiliser Google Colab.

## Utilisation

### Étape 1 : Télécharger les Fichiers

Téléchargez les fichiers `sizes.csv` et `notebook.ipynb` depuis ce repository sur votre machine locale.

### Étape 2 : Importer les Fichiers dans Google Colab

1. Ouvrez [Google Colab](https://colab.research.google.com/) dans votre navigateur.
2. Cliquez sur **File > Upload notebook** et importez le fichier `notebook.ipynb`.
3. Pour importer le fichier `sizes.csv`, exécutez la cellule suivante dans le notebook pour ouvrir le sélecteur de fichiers et téléchargez `sizes.csv` :

```python
from google.colab import files
uploaded = files.upload()
```

### Étape 3 : Exécuter le Notebook

Une fois le fichier `sizes.csv` importé, exécutez chaque cellule du notebook `notebook.ipynb` une par une en cliquant sur le bouton de lecture (play) à gauche de chaque cellule.
Le notebook est conçu pour charger les données, entraîner le modèle, et déployer l'application Streamlit via ngrok.

### Fichiers Importants

#### `sizes.csv`

Ce fichier contient les données utilisées pour entraîner le modèle de machine learning.

#### `notebook.ipynb`

Ce notebook Jupyter contient le code pour :

- Charger et explorer les données
- Préparer et nettoyer les données
- Entraîner et évaluer le modèle de machine learning
- Générer des prédictions
- Déployer l'application Streamlit

### Auteurs

- Romain Brosolo
- Younes Baali
