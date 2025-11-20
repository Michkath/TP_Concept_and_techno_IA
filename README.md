# 🏦 Prédiction de Risque de Crédit (Home Credit)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/Michkath/TP_Concept_and_techno_IA/blob/main/exploration_tp-checkpoint.ipynb)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

> **Note :** Ce projet est présenté sous forme de Notebook Jupyter.  
> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](LIEN_VERS_TON_NOTEBOOK_SUR_GITHUB)

## 📄 Contexte du Projet
De nombreuses personnes peinent à obtenir des prêts bancaires en raison d'antécédents de crédit insuffisants ou inexistants. **Home Credit** cherche à élargir l'inclusion financière en offrant une expérience d'emprunt positive et sûre à cette population non bancarisée.

**L'objectif de ce projet** est d'utiliser les données (historique, données alternatives) pour prédire la capacité de remboursement d'un client et ainsi assurer que les clients capables de rembourser ne soient pas rejetés.

## 🎯 Objectifs Business
* **Minimiser le risque financier** en détectant les clients susceptibles de faire défaut.
* **Maximiser l'approbation** des clients solvables injustement rejetés.
* **Interprétabilité :** Comprendre *pourquoi* un client est classé à risque.

## 🛠️ Stack Technique
* **Langage :** Python 3.x
* **Manipulation de données :** Pandas, NumPy (Dataset de +300 000 lignes)
* **Visualisation (EDA) :** Matplotlib, Seaborn
* **Machine Learning :** Scikit-Learn (Random Forest, XGBoost/LightGBM, Régression Logistique)
* **Métriques :** ROC-AUC, F1-Score

## ⚙️ Méthodologie & Démarche
Mon analyse dans le notebook suit les étapes suivantes :

1.  **Exploration des Données (EDA) :**
    * Analyse de la distribution de la variable cible (Déséquilibre de classe).
    * Étude des corrélations et visualisation des variables clés (Revenus, Âge, Type d'emploi).
    
2.  **Nettoyage & Préparation (Feature Engineering) :**
    * Traitement des valeurs manquantes et aberrantes.
    * Encodage des variables catégorielles (One-Hot Encoding).
    * Création de nouvelles features métiers (ex: Ratio Crédit/Revenus).

3.  **Modélisation :**
    * Gestion du déséquilibre des données (ex: SMOTE ou class_weight).
    * Comparaison de plusieurs algorithmes.
    * Optimisation des hyperparamètres.

4.  **Interprétabilité :**
    * Analyse de l'importance des features (Feature Importance) pour expliquer les décisions du modèle.

## 📊 Résultats Clés
* **Performance :** Le modèle final atteint un score **ROC-AUC de 0.XX** (Remplacer par ton score).
* **Facteurs déterminants :** L'analyse a révélé que les variables les plus influentes sur le risque de défaut sont [Variable A], [Variable B] et [Variable C].


## 🚀 Comment exécuter ce projet ?
1.  Cloner le dépôt :
    ```bash
    git clone [https://github.com/michkath-aboudou/NOM_DU_REPO.git](https://github.com/michkath-aboudou/NOM_DU_REPO.git)
    ```
2.  Installer les dépendances :
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Lancer le notebook :
    ```bash
    jupyter notebook NOM_DU_FICHIER.ipynb
    ```

---
*Projet réalisé par [Michkath ABOUDOU](https://www.linkedin.com/in/michkath-aboudou/)*
