# 🧬 Mini Projet BioALGO — Alignement de Séquences

Ce projet a été réalisé dans le cadre du module **BioAlgorithmes** (M1 Bio-Informatique) à l’**Université des Sciences et de la Technologie Houari Boumediene (USTHB)**.  
Il porte sur l’**alignement de séquences biologiques** (ADN, ARN ou protéines) à l’aide de différents algorithmes, avec une implémentation complète en **Python (Jupyter Notebook)**.

> 📄 Le rapport complet `MiniProjet_BioALGO.pdf` accompagne ce projet et détaille la théorie, les algorithmes et les résultats expérimentaux.

---

## 🚀 Objectifs

- Comprendre les **fondements de l’alignement de séquences**
- Implémenter les algorithmes :
  - 🔹 Needleman-Wunsch (alignement global)
  - 🔹 Smith-Waterman (alignement local)
  - 🔹 Alignement multiple (approche progressive)
- Évaluer les **performances** (temps d’exécution, score)
- Comparer différentes **méthodes d’alignement**
- Appliquer ces concepts à des **cas biologiques réels**

---

## 🧪 Fonctionnalités

- Alignement de deux séquences (global/local)
- Alignement multiple de séquences (via profil)
- Visualisation des résultats et scores
- Analyse des performances (temps et précision)
- Tests sur des séquences de longueurs variables

---

## 📘 Algorithmes utilisés

| Algorithme            | Type              | Complexité           |
| --------------------- | ----------------- | -------------------- |
| Needleman-Wunsch      | Alignement global | `O(n × m)`           |
| Smith-Waterman        | Alignement local  | `O(n × m)`           |
| Alignement progressif | Multiple          | Approche heuristique |

- 📏 Matrice de similarité utilisée : **BLOSUM62**
- 📉 Pénalité de gap : **-2**

---

## 📊 Résultats expérimentaux

| Longueur (L) | NW Score | SW Score | NW Temps (s) | SW Temps (s) |
| ------------ | -------- | -------- | ------------ | ------------ |
| 100          | 319      | 359      | 0.0355       | 0.0507       |
| 300          | 937      | 1056     | 0.3476       | 0.4403       |
| 700          | 2142     | 2382     | 1.8183       | 2.2630       |

_→ Voir graphiques et tableau complet dans le rapport PDF._

---

## 📦 Fichiers

- `app.ipynb` — Notebook principal avec les implémentations
- `MiniProjet_BioALGO.pdf` — Rapport de projet avec explications, résultats et conclusion

---

## 🖥️ Prérequis

- Python 3.7+
- Jupyter Notebook
- `numpy`, `matplotlib` (pour les graphiques)

Installez les dépendances si nécessaire :

```bash
pip install numpy matplotlib
```
