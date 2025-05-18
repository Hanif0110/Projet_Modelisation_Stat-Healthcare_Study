# 🏥 Projet de Modélisation Statistique – Analyse du Parcours Patient

## 🎯 Objectif du projet

Étudier les facteurs influençant :
- Le **coût des soins médicaux** (`Billing Amount`)
- La **durée d’hospitalisation** (`Hospital Stay (Days)`)
- Les **résultats médicaux** (`Test Results`)

à partir de données synthétiques de patients hospitalisés, afin de :
- Mieux comprendre les tendances hospitalières
- Identifier des leviers d’optimisation de la gestion médicale et économique
- Préparer des modèles prédictifs pour les coûts et les résultats médicaux

---

## 📁 Données utilisées

Le jeu de données synthétique contient :
- **Données personnelles** : `Age`, `Gender`, `Blood Type`
- **Données médicales** : `Medical Condition`, `Medication`, `Test Results`
- **Données administratives** : `Admission Type`, `Date of Admission`, `Discharge Date`
- **Données financières** : `Billing Amount`, `Insurance Provider`

---

## 🧪 Plan de l’analyse

Chaque partie est réalisée dans un notebook Jupyter, avec :
- Des **cellules Markdown** pour expliquer les notions et formules (LaTeX)
- Des **cellules Python** pour exécuter le code et afficher les résultats

### 🟨 Partie 1 – Statistiques univariées  
**But** : Explorer la distribution de `Billing Amount` (moyenne, dispersion, extrêmes)

### 🟩 Partie 2 – Corrélation  
**But** : Mesurer le lien linéaire entre `Age` et `Billing Amount`

### 🟦 Partie 3 – Test de moyenne (genre)  
**But** : Comparer les coûts moyens hommes vs femmes

### 🟪 Partie 4 – ANOVA (type d’admission)  
**But** : Vérifier si le motif d’admission influence le coût

### 🟥 Partie 5 – Valeurs aberrantes  
**But** : Détecter et traiter les factures incohérentes ou extrêmes

### 🟧 Partie 6 – Données manquantes  
**But** : Identifier et gérer les valeurs manquantes

### 🟫 Partie 7 – Régression linéaire multiple  
**But** : Modéliser `Billing Amount` à partir de plusieurs variables explicatives

### 🟨 Partie 8 – Régression polynomiale  
**But** : Capturer d’éventuelles relations non linéaires sur `Billing Amount`

### 🟩 Partie 9 – Classification supervisée  
**But** : Prédire `Test Results` (Normal / Abnormal / Inconclusive) via régression logistique

---

## 📚 Technologies et bibliothèques

- **Langage** : Python (Jupyter Notebook)  
- **Manipulation et calcul** : pandas, numpy  
- **Visualisation** : matplotlib, seaborn  
- **Statistiques et tests** : scipy.stats, statsmodels  
- **Machine Learning** : scikit-learn  
- **Formules** : LaTeX dans les cellules Markdown  

---

## 🤝 Collaboration

Ce projet est développé en groupe.  
Pour contribuer :
1. Crée une branche dédiée  
2. Ajoute ou modifie du contenu dans le notebook **etude.ipynb**  
3. Propose une pull request dans ce dépôt  

---

> **Remarque** : Les scripts Python et les formules LaTeX sont commentés et justifiés dans le notebook pour assurer la traçabilité de chaque étape d’analyse.  
