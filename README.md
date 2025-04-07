# 🏥 Projet de Modélisation Statistique – Analyse du Parcours Patient

## 🎯 Objectif du projet

Ce projet a pour objectif d'étudier les facteurs influençant :

- Le **coût des soins médicaux** (`Billing Amount`)
- La **durée d’hospitalisation** (`Hospital Stay`)
- Les **résultats médicaux** (`Test Results`)

à partir de données patients synthétiques, dans le but de :

- Mieux comprendre les tendances hospitalières,
- Identifier des leviers d’optimisation de la gestion médicale et économique,
- Préparer un modèle prédictif sur les résultats médicaux.

---

## 📁 Données utilisées

Le dataset est un jeu de données **synthétique** représentant des informations réalistes sur des patients hospitalisés :
- Données personnelles : `Age`, `Gender`, `Blood Type`
- Données médicales : `Medical Condition`, `Test Results`, `Medication`
- Données administratives : `Admission Type`, `Date of Admission`, `Discharge Date`
- Données financières : `Billing Amount`, `Insurance Provider`

---

## 🧪 Étapes de l’analyse

Chaque partie ci-dessous s’intègre dans un notebook Jupyter où **l'analyse statistique est mise en avant** avec des justifications théoriques (formules LaTeX) et des visualisations.

### 🟨 Partie 1 – Statistiques univariées
> **Objectif** : Étudier la distribution de la variable `Billing Amount` pour identifier sa tendance centrale, sa dispersion et ses extrêmes.

---

### 🟩 Partie 2 – Corrélation
> **Objectif** : Évaluer le lien entre l’âge du patient et le montant facturé (`Age` vs `Billing Amount`) pour détecter une possible influence linéaire.

---

### 🟦 Partie 3 – Test de moyenne (par genre)
> **Objectif** : Vérifier si les coûts moyens diffèrent entre hommes et femmes (`Billing Amount` selon `Gender`).

---

### 🟪 Partie 4 – ANOVA selon le type d’admission
> **Objectif** : Mesurer l’impact du `Admission Type` sur le coût (`Billing Amount`), et détecter des différences significatives.

---

### 🟥 Partie 5 – Valeurs aberrantes
> **Objectif** : Identifier les factures incohérentes (trop faibles ou négatives) et les outliers afin d'assainir les données.

---

### 🟧 Partie 6 – Données manquantes
> **Objectif** : Diagnostiquer et traiter les valeurs manquantes pour éviter les biais d’analyse et assurer la robustesse des modèles.

---

### 🟫 Partie 7 – Régression linéaire
> **Objectif** : Prédire le coût (`Billing Amount`) à partir des variables explicatives : âge, durée d’hospitalisation, type d’admission, etc.

---

### 🟨 Partie 8 – Analyse de la variable `Test Results`
> **Objectif** : Étudier la distribution et les facteurs associés aux résultats médicaux (`Normal`, `Abnormal`, `Inconclusive`) afin de préparer une tâche de classification.

---

### 🟩 Partie 9 – Classification supervisée (à venir)
> **Objectif** : Construire un modèle de prédiction des `Test Results` à partir des variables disponibles. Cette partie mobilisera des algorithmes de machine learning supervisé.

---

## 📚 Technologies utilisées

- Python (Jupyter)
- Pandas, NumPy, Matplotlib, Seaborn
- SciPy, Statsmodels
- LaTeX pour l’affichage des formules

---
