# 🧠 Projet d'AutoML avec PyCaret

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![PyCaret](https://img.shields.io/badge/PyCaret-3.0-green)](https://pycaret.gitbook.io/docs/)

Ce projet démontre comment automatiser la comparaison de modèles de classification à l'aide de **PyCaret**, une bibliothèque low-code pour le Machine Learning en Python.

## 📁 Contenu du dépôt

- `compare_models.py` : Script principal d'exécution du workflow AutoML
- `resultats_prepares.csv` : Jeu de données après traitement PyCaret (généré automatiquement)
- `metric.PNG` : Visualisation des performances du modèle sélectionné

## ⚙️ Prérequis

Créez un environnement virtuel (recommandé avec Anaconda) :

```bash
conda create -n myenv python=3.9 -y
conda activate myenv
pip install pycaret==3.0.0 scikit-learn==1.1.3 pandas
```

## 🚀 Exécution du script

```bash
python compare_models.py
```

Le script :
- Télécharge les données
- Configure l'environnement PyCaret
- Compare plusieurs modèles
- Finalise le meilleur modèle
- Exporte les résultats nettoyés en CSV

## 📊 Exemple de sortie

![Graphique de performances](./metric.PNG)

Le modèle le plus performant est affiché avec ses métriques : `Accuracy`, `Recall`, `F1`, etc.

## 📦 Dépendances

- `pycaret==3.0.0`
- `scikit-learn==1.1.3`
- `pandas`

## 🧯 Résolution de problèmes

**Erreur fréquente :**
```
AttributeError: 'Simple_Imputer' object has no attribute 'target_variable'
```
✅ Solution :
- Downgrader `scikit-learn` à la version 1.1.3

## 📜 Licence

Projet sous licence MIT — libre d’utilisation, modification et distribution.

