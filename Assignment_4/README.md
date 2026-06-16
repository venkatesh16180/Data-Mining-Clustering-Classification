# Assignment 4 — Decision Tree Classification
**Course: Data Mining & Discovery | University of Arizona**

## 📌 Objective
Build a Decision Tree classifier to predict `signs_of_mental_illness` 
from the Fatal Police Shootings dataset, then regularize and compare 
model performance.

## 📊 Dataset
Fatal Police Shootings dataset — see Assignment 1 for source file.

## 🔑 Key Tasks
- Encoded categorical variables using `LabelEncoder`
- Split data into train/test sets (80/20, random_state=101)
- Built Decision Tree model using **entropy criterion**
- Visualized the full decision tree using Graphviz
- Evaluated with confusion matrix, accuracy, and precision scores
- Regularized the model with `max_depth=6`, `min_samples_split=3` 
  and compared performance against the unregularized baseline

## 📊 Results
- Base model vs. regularized model performance compared via confusion 
  matrix and accuracy score
- Regularization reduced overfitting while maintaining predictive power

## 🛠️ Tools & Technologies
`Python` `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `Graphviz` 
`Jupyter Notebook`

## 📁 Files
| File | Description |
|---|---|
| `Assignment - 4.ipynb` | Decision Tree classification notebook |
