# Assignment 5 — K-Means & K-Medoids Clustering
**Course: Data Mining & Discovery | University of Arizona**

## 📌 Objective
Apply unsupervised clustering models — K-Means and K-Medoids (PAM) — 
to discover hidden patterns in the Fatal Police Shootings dataset. 
Compare results, visualize clusters, and interpret findings.

## 📊 Dataset
Fatal Police Shootings dataset — see Assignment 1 for source file.

## 🔑 Key Tasks
- Preprocessed data: dropped irrelevant columns, encoded categoricals, 
  applied StandardScaler
- Applied **Elbow method** (k=1 to 10) to identify optimal cluster count
- Built **K-Means** model with 3 optimal clusters; assigned and 
  profiled cluster labels
- Built **K-Medoids (PAM)** model using sklearn-extra; validated with 
  **Silhouette scores** across k=2 to 10
- Visualized and interpreted cluster profiles — identifying dominant 
  characteristics of each group

## 📊 Key Finding
Optimal cluster count: **3 clusters** — identified via Elbow method 
and confirmed through cluster profile analysis showing distinct 
demographic and behavioral patterns across groups.

## 🛠️ Tools & Technologies
`Python` `Scikit-learn` `sklearn-extra (KMedoids)` `Pandas` `NumPy` 
`Matplotlib` `Seaborn` `Jupyter Notebook`

## 📁 Files
| File | Description |
|---|---|
| `Assignment_5.ipynb` | K-Means and K-Medoids clustering notebook |
