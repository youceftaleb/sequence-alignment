# 🧬 BioALGO Mini Project — Sequence Alignment

This project was developed as part of the **BioALGO** course (M1 Bioinformatics) at the **University of Science and Technology Houari Boumediene (USTHB)**.  
It focuses on **biological sequence alignment algorithms**, with full implementations in Python (via Jupyter Notebook).

📄 A detailed report (`MiniProjet_BioALGO.pdf`, in French) is included, explaining the theory, algorithms, experimental results, and analysis.

---

## 🚀 Objectives

- Understand core concepts of **DNA/protein sequence alignment**
- Implement:
  - 🔹 Needleman-Wunsch (global alignment)
  - 🔹 Smith-Waterman (local alignment)
  - 🔹 Progressive multiple sequence alignment
- Analyze execution time and alignment score
- Compare algorithmic strategies
- Apply these to real-world biological data

---

## 🧪 Features

- Global and local pairwise alignment
- Multiple sequence alignment using a profile-based progressive approach
- Alignment score and runtime analysis
- Visual output and performance graphs
- Tested with sequences of various lengths and quantities

---

## 📘 Algorithms

| Algorithm        | Type               | Complexity      |
| ---------------- | ------------------ | --------------- |
| Needleman-Wunsch | Global alignment   | `O(n × m)`      |
| Smith-Waterman   | Local alignment    | `O(n × m)`      |
| Progressive MSA  | Multiple alignment | Heuristic-based |

- 🔢 Similarity matrix: **BLOSUM62**
- ➖ Gap penalty: **-2**

---

## 📊 Sample Results

| Sequence Length | NW Score | SW Score | NW Time (s) | SW Time (s) |
| --------------- | -------- | -------- | ----------- | ----------- |
| 100             | 319      | 359      | 0.0355      | 0.0507      |
| 300             | 937      | 1056     | 0.3476      | 0.4403      |
| 700             | 2142     | 2382     | 1.8183      | 2.2630      |

_More results, graphs, and commentary are available in the report._

---

## 📂 Files

- `app.ipynb` — Main Jupyter Notebook with code implementations
- `MiniProjet_BioALGO.pdf` — Full project report (in French)

---

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook
- `numpy`, `matplotlib`

Install required packages:

```bash
pip install numpy matplotlib
```

## 🌐 Other Languages

📄 This README is also available in [🇫🇷 Français](README_FR.md)
