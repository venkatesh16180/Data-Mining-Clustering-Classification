# Assignment 6 — DBSCAN, OPTICS & BIRCH Clustering
**Course: Data Mining & Discovery | University of Arizona**

## 📌 Objective
Apply density-based and hierarchical clustering models — DBSCAN, 
OPTICS, and BIRCH — to the Fatal Police Shootings dataset. Compare 
results across all three algorithms and interpret cluster structures.

## 📊 Dataset
Fatal Police Shootings dataset — see Assignment 1 for source file.

## 🔑 Key Tasks
- Applied **DBSCAN** (eps=0.1, min_samples=9) — identified core, 
  border, and noise points; visualized cluster distribution
- Applied **OPTICS** (eps=0.1, min_samples=9) — compared reachability 
  plot against DBSCAN output
- Applied **BIRCH** (n_clusters=3) — hierarchical clustering for 
  scalable pattern discovery
- Compared all three algorithms on cluster count, noise handling, 
  and shape detection capability
- Visualized cluster distributions using Seaborn countplots

## 📊 Key Insight
DBSCAN and OPTICS effectively identified irregular cluster shapes and 
noise points that grid-based methods like K-Means cannot detect — 
demonstrating the value of density-based approaches on real-world data.

## 🛠️ Tools & Technologies
`Python` `Scikit-learn (DBSCAN, OPTICS, Birch)` `Pandas` `NumPy` 
`Matplotlib` `Seaborn` `Jupyter Notebook`

## 📁 Files
| File | Description |
|---|---|
| `Assignment - 6.ipynb` | DBSCAN, OPTICS, and BIRCH clustering notebook |
