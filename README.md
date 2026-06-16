# Data Mining — Clustering & Classification Pipeline
**Course: Data Mining & Discovery | University of Arizona**

---

## 📌 Overview
A comprehensive, end-to-end data mining pipeline applied to the 
**Fatal Police Shootings dataset** across 6 progressive assignments. 
The project covers the full data science workflow from raw data 
exploration to advanced unsupervised clustering — implementing and 
comparing 6+ machine learning models.

---

## 📁 Repository Structure
Data-Mining-Clustering-Classification/

│

├── Assignment_1/     # EDA & Python Fundamentals

├── Assignment_2/     # Statistical Analysis & Outlier Detection

├── Assignment_3/     # Data Preprocessing & Feature Engineering

├── Assignment_4/     # Decision Tree Classification

├── Assignment_5/     # K-Means & K-Medoids Clustering

├── Assignment_6/     # DBSCAN, OPTICS & BIRCH Clustering

└── README.md

---

## 📊 Dataset
**Fatal Police Shootings in the US — Washington Post**
- Included in Assignment 1 folder
- Features: victim demographics, manner of death, armed status, 
  mental illness indicators, location, date

---

## 🧠 Project Progression

| Assignment | Focus | Models/Techniques |
|---|---|---|
| 1 | EDA & Python Fundamentals | Pandas, NumPy, statistical metrics |
| 2 | Statistical Analysis | Outlier detection (IQR), missing value analysis |
| 3 | Data Preprocessing | Scaling, transformation, correlation, sampling |
| 4 | Supervised Learning | Decision Tree (entropy criterion, regularization) |
| 5 | Unsupervised Learning | K-Means, K-Medoids (PAM), Elbow method, Silhouette |
| 6 | Density-based Clustering | DBSCAN, OPTICS, BIRCH |

---

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Language | Python |
| ML Models | Scikit-learn (DecisionTreeClassifier, KMeans, DBSCAN, OPTICS, Birch) |
| Clustering | sklearn-extra (KMedoids) |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Evaluation | Silhouette Score, Confusion Matrix, Accuracy, Precision |
| Environment | Jupyter Notebook |

---

## 🔑 Key Results
- Decision Tree achieved strong classification performance predicting 
  `signs_of_mental_illness` with regularization (max_depth=6)
- Optimal K-Means clusters: **3 clusters** identified via Elbow method
- K-Medoids validated cluster stability via Silhouette score analysis
- DBSCAN/OPTICS identified noise points and irregular cluster shapes 
  outperforming grid-based methods on non-spherical data
- BIRCH demonstrated scalable hierarchical clustering on the full dataset

---

## 👤 Author
**Venkateshwara Chowdary Tallapaneni**
MS Information Sciences (Machine Learning) | University of Arizona
[LinkedIn](https://www.linkedin.com/in/venkateshwara-chowdary-tallapaneni) | 
[GitHub](https://github.com/venkatesh16180)
