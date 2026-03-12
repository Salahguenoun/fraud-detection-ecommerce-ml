# Détection de fraude dans les transactions e-commerce par Machine Learning

## Présentation du projet

Ce dépôt contient le notebook utilisé pour mon mémoire de fin d’études.

L’objectif de ce projet est de détecter les transactions frauduleuses dans le e-commerce à l’aide de techniques de **machine learning**.

L’étude s’appuie sur le **dataset IEEE-CIS Fraud Detection** et compare plusieurs modèles supervisés et non supervisés afin d’identifier les transactions suspectes.

---

## Modèles utilisés

Les modèles suivants ont été testés :

* Régression logistique
* Random Forest
* XGBoost
* Isolation Forest

Le modèle le plus performant est **XGBoost**, avec les performances suivantes :

* Recall (fraude) : 67 %
* Précision (fraude) : 50 %
* F1-score : 57 %
* AUC : 0.9386

---

## Dataset

Le dataset utilisé est :

**IEEE-CIS Fraud Detection**

Il peut être téléchargé sur Kaggle :

https://www.kaggle.com/competitions/ieee-fraud-detection

Fichiers nécessaires :

* `train_transaction.csv`
* `train_identity.csv`

Ces fichiers ne sont pas inclus dans ce dépôt en raison de leur taille.

---

## Comment exécuter le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/fraud-detection-ecommerce-ml.git
cd fraud-detection-ecommerce-ml
```

---

### 2. Installer les dépendances

```bash
pip install -r requirements.txt
```

---

### 3. Télécharger le dataset

Télécharger les fichiers depuis Kaggle :

* `train_transaction.csv`
* `train_identity.csv`

Puis placer ces fichiers dans votre environnement de travail (local ou Google Drive si vous utilisez Google Colab).

Adapter ensuite le **chemin d’accès aux données dans le notebook** si nécessaire.

---

### 4. Lancer le notebook

Ouvrir le fichier :

```
Mémoire_finale.ipynb
```

et exécuter les cellules dans l’ordre.

---

## Auteur

Salah GUENOUN
Mastère Big Data & Data Science en Finance
Paris
