# 🧹 Music Tour Data Cleaning (Python & Pandas)

[English Version](#english-version) | [Version Française](#version-française)

---

## English Version

### 📝 Project Overview
This project, developed as part of my **AI Master's program**, focuses on cleaning a raw CSV dataset of worldwide music tours. It demonstrates professional data preprocessing skills required for freelance data analysis.

### ⚙️ Cleaning Pipeline
The script (`clean_data.py`) performs the following operations:
* **Text Scrubbing:** Removes Wikipedia-style citations (e.g., `[1]`) using Regex.
* **Financial Formatting:** Strips currency symbols (`$`) and commas.
* **Data Integrity:** * Uses `Int64` for rankings to avoid the `.0` float issue.
    * Preserves date formats correctly.

---

## Version Française

### 📝 Présentation du Projet
Réalisé dans le cadre de mon **Master 2 en Intelligence Artificielle**, ce projet porte sur le nettoyage d'un jeu de données concernant les tournées musicales. Il illustre ma maîtrise du **Data Preprocessing**, une étape cruciale en IA.

### ⚙️ Pipeline de Nettoyage
Le script assure la transformation des données "brutes" en données "propres" :
* **Nettoyage Textuel :** Suppression des notes (ex: `[1]`) via des expressions régulières (Regex).
* **Normalisation Financière :** Retrait des symboles `$` et des virgules pour permettre des calculs.
* **Gestion des Types :**
    * Utilisation du format `Int64` pour éviter les décimales inutiles (`.0`).
    * Conservation des dates intactes.

---

## 📁 Structure
* `CT.csv`: Raw data / Données brutes.
* `clean_data.py`: Cleaning script / Script de nettoyage.
