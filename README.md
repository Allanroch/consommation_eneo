# 📊 Analyse de Séries Temporelles — Consommation ENEO

![Python](https://img.shields.io/badge/Python-Analyse%20de%20données-blue)
![Statsmodels](https://img.shields.io/badge/Modèle-ARIMA%2FSARIMA-green)
![Excel](https://img.shields.io/badge/Outil-Excel-orange)
![Statut](https://img.shields.io/badge/Projet-Académique-success)

---

## 🧠 Contexte du projet

Dans le cadre du cours **Séries Temporelles (SDIA3 — ENSPD)**, ce projet consiste à analyser une série temporelle réelle de consommation d’électricité (ENEO) afin de produire des prévisions fiables pour aider à la prise de décision.

L’étude combine :

* 📉 des méthodes classiques (Excel)
* 🤖 des méthodes avancées (Python — ARIMA/SARIMA)

---

## 🎯 Objectif général

Construire une chaîne complète de prévision capable d’anticiper la consommation future d’électricité à partir de données historiques.

---

## 🔍 Objectifs spécifiques

### 📈 Analyse exploratoire

* Visualiser la série temporelle
* Identifier la tendance
* Détecter la saisonnalité
* Évaluer le niveau de bruit

### 📉 Décomposition classique (Excel)

* Extraire la composante tendance
* Calculer les coefficients saisonniers
* Analyser les résidus
* Choisir entre modèle additif ou multiplicatif

### 🔮 Prévisions classiques

* Appliquer le lissage exponentiel
* Produire des prévisions sur 12 périodes
* Interpréter les résultats

### 🤖 Modélisation avancée (Python)

* Tests de stationnarité (ADF, KPSS)
* Différenciation si nécessaire
* Identification des ordres ARIMA/SARIMA
* Estimation et comparaison des modèles
* Validation par analyse des résidus (ACF, PACF, Ljung-Box)

### 📊 Prévisions finales

* Générer les valeurs futures
* Visualiser historique vs prévisions
* Interpréter pour la prise de décision

### ⚖️ Comparaison des méthodes

* Comparer Excel vs ARIMA/SARIMA
* Évaluer la fiabilité
* Discuter les limites

---

## 🛠️ Technologies utilisées

**Outils**

* Excel
* Python
* Jupyter Notebook

**Bibliothèques**

* pandas
* numpy
* matplotlib
* statsmodels

---

## 📁 Structure du projet

```text
📦 series_temporelles_SDIA3
 ┣ 📊 Excel.xlsx
 ┣ 🐍 Analyse_Python.ipynb
 ┣ 📄 Rapport.pdf
 ┣ 🎥 Video.mp4
 ┗ 📘 README.md
```

---

## 🚀 Compétences développées

* Analyse de séries temporelles
* Data Analytics
* Forecasting
* Modélisation ARIMA/SARIMA
* Tests de stationnarité
* Visualisation de données
* Interprétation orientée décision

---

## 🧪 Analyse comparative des méthodes

### 🟠 Méthode classique (Excel)

**Avantages**

* Simple à mettre en œuvre
* Rapide pour une première analyse
* Bonne visualisation
* Accessible aux débutants

**Limites**

* Puissance de modélisation limitée
* Peu scalable
* Validation statistique moins rigoureuse
* Gestion limitée des structures complexes

---

### 🔵 Méthode avancée (Python — ARIMA/SARIMA)

**Avantages**

* Rigueur statistique élevée
* Meilleure prise en compte de la dépendance temporelle
* Estimation automatique des paramètres
* Diagnostics complets des résidus
* Adaptée aux grandes données
* Standard industriel en data science

**Limites**

* Nécessite des compétences en programmation
* Mise en œuvre plus complexe

---

## 🏆 Conclusion

Bien que l’analyse sous Excel constitue une étape exploratoire utile, **la modélisation avancée sous Python (ARIMA/SARIMA) s’avère la méthode la plus performante et la plus fiable pour la prévision**.

Elle permet :

* ✅ une validation statistique plus robuste
* ✅ une meilleure modélisation de la dynamique temporelle
* ✅ des prévisions plus précises
* ✅ une approche conforme aux standards professionnels

👉 **La méthode Python est donc recommandée pour une utilisation en contexte réel d’entreprise.**

---

## 👨‍💻 Auteur

**Allan Nenkam**
SDIA3 — ENSPD
Année académique : 2025-2026

---
