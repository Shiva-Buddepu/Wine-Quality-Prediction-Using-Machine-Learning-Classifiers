#  Wine Quality Prediction Using Machine Learning Classifiers

This project focuses on predicting the **quality of red wine** based on various physicochemical attributes using different machine learning models. The goal is to build a robust model that can classify wine quality effectively and help in quality assessment tasks for winemakers and researchers.

---

## Dataset

**File Used:** `winequality-red.csv`  
The dataset contains physicochemical properties of red wine and their corresponding quality ratings.  

| Feature | Description |
|----------|-------------|
| fixed acidity | Amount of non-volatile acids |
| volatile acidity | Amount of acetic acid in wine |
| citric acid | Adds freshness and flavor |
| residual sugar | Remaining sugar after fermentation |
| chlorides | Salt content |
| free sulfur dioxide | Free form of SO₂ (antioxidant) |
| total sulfur dioxide | Total SO₂ in the wine |
| density | Density of the wine |
| pH | Acidity or basicity |
| sulphates | Additive contributing to SO₂ levels |
| alcohol | Alcohol percentage |
| quality | Output variable (score between 0–10) |

---

##  Exploratory Data Analysis (EDA)

Explored the dataset using:
- **Matplotlib** and **Seaborn** for visualization
- Distribution plots and correlation heatmaps
- Pairwise feature relationships to understand quality impact factors

---

##  Machine Learning Models Used

Three supervised classification algorithms were implemented and compared:

1. **Random Forest Classifier**
2. **Stochastic Gradient Descent (SGD) Classifier**
3. **Support Vector Classifier (SVC)**

Each model was trained, tested, and evaluated based on performance metrics like **accuracy**, **precision**, and **F1-score**.

---

##  Model Optimization

To enhance the model performance, cross-validation and hyperparameter tuning were performed:

- **Grid Search CV** → for hyperparameter optimization  
- **Cross Validation Score** → for reliable performance estimation  

---

##  Workflow

1. Import necessary libraries  
2. Load and explore the dataset  
3. Visualize data distributions and correlations  
4. Split dataset into training and testing sets  
5. Train models (Random Forest, SGD, SVC)  
6. Evaluate using accuracy and confusion matrix  
7. Apply **Grid Search CV** and **Cross Validation** for tuning  
8. Compare and select the best performing model  

---
