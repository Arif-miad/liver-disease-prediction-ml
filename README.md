# liver-disease-prediction-ml# 🧬 Liver Disease Prediction — EDA + 10 ML Models

This repository contains a complete **end-to-end pipeline** to predict **Liver Disease Status** using clinical biomarkers and lifestyle features.
The project includes **Exploratory Data Analysis (EDA), preprocessing, feature encoding, scaling, and evaluation of 10 machine learning models**.

---

## 📂 Dataset

The dataset includes **12 features**:

| Feature              | Description                           |
| -------------------- | ------------------------------------- |
| Bilirubin            | Blood bilirubin level                 |
| ALT                  | Alanine aminotransferase              |
| AST                  | Aspartate aminotransferase            |
| Alkaline_Phosphatase | Liver enzyme level                    |
| Albumin              | Serum albumin                         |
| BMI                  | Body mass index                       |
| Alcohol_Use          | Alcohol consumption level             |
| Medication           | Type of medication used               |
| Gender               | Male / Female                         |
| Smoking              | Smoking status                        |
| Diet                 | Healthy / Unhealthy                   |
| Liver_Disease_Status | Target (Healthy / At_Risk / Diseased) |

---

## 🧹 Data Preprocessing

* Handled missing values (median for numeric, mode/Unknown for categorical)
* Label encoding for categorical variables
* MinMax scaling for numeric features
* Outlier detection using boxplots
* Feature correlation analysis

---

## 📊 Exploratory Data Analysis (EDA)

* Distribution plots for numeric features (histograms, KDE)
* Boxplots for feature comparison
* Countplots for categorical features
* Feature vs Target analysis
* Correlation heatmap & pairplots
* Class distribution visualization

---

## 🤖 Machine Learning Models

10 models trained and evaluated:

| Model                           |
| ------------------------------- |
| Logistic Regression             |
| K-Nearest Neighbors (KNN)       |
| Support Vector Classifier (SVC) |
| Decision Tree                   |
| Random Forest                   |
| Gradient Boosting               |
| XGBoost                         |
| LightGBM                        |
| CatBoost                        |
| Naive Bayes                     |

**Metrics used:** Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC.

---

## 📈 Results Visualization

* Confusion matrices for top models
* ROC-AUC comparison
* Feature importance (Tree-based models)

📸 Screenshots / Visualizations (replace with your own images):

```
screenshots/eda.png
screenshots/confusion_matrix.png
screenshots/roc_curve.png
screenshots/feature_importance.png
```

---

## 🏆 Best Performing Model

| Model                                           | Accuracy |
| ----------------------------------------------- | -------- |
| Random Forest                                   | 100%      |
|  |          |

---

## 🛠 Project Structure

```
liver-disease-prediction-ml/
├── data/                       # Dataset CSV file
├── notebooks/                  # Jupyter notebooks
│   └── liver_disease_eda_ml.ipynb
├── screenshots/                # EDA and model plots
├── models/                     # Saved ML models
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/Arif-miad/liver-disease-prediction-ml.git
cd liver-disease-prediction-ml

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook notebooks/liver_disease_eda_ml.ipynb
```

---

## 👨‍💻 Author

**Arif Mia**
Machine Learning Engineer
📧 Email: [arifmiahcse@gmail.com](mailto:arifmiahcse@gmail.com)
🔗 Kaggle: [https://www.kaggle.com/miadul](https://www.kaggle.com/miadul)
🔗 GitHub: [https://github.com/Arif-miad](https://github.com/Arif-miad)
🔗 LinkedIn: [https://www.linkedin.com/in/arif-miah-8751bb217/](https://www.linkedin.com/in/arif-miah-8751bb217/)
