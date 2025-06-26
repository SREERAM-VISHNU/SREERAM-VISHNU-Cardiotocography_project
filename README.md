# Cardiotocography_Project

This project applies machine learning techniques to classify fetal health based on cardiotocography (CTG) data. The model predicts whether a fetus is **normal**, **suspect**, or **pathological**, helping identify early signs of fetal distress or abnormalities.

## 📊 Dataset

- Source: [UCI Machine Learning Repository – Cardiotocography Data Set](https://archive.ics.uci.edu/ml/datasets/Cardiotocography)
- Features: 21 numerical attributes extracted from fetal heart rate and uterine contraction signals.
- Target variable: `fetal_health` (Normal = 1, Suspect = 2, Pathological = 3)

## 🔧 Technologies Used

- **Python**
- **Pandas**, **NumPy** for data handling
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing, modeling, and evaluation
- **XGBoost**, **CatBoost**, **RandomForestClassifier** for classification

## 📌 Project Highlights

- Explored and cleaned the CTG dataset
- Visualized class imbalance and feature distribution
- Trained and compared several classification models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
  - CatBoost
- Performed hyperparameter tuning using `GridSearchCV`
- Evaluated models using:
  - Confusion matrix
  - Classification report
  - ROC-AUC score
- Achieved best results with **XGBoost and CatBoost**

## 📈 Results

- High accuracy (~97%) and strong ROC-AUC scores across all classes
- Demonstrated effective application of ML in a healthcare context

## 📁 How to Use

1. Clone this repository or open the notebook in Google Colab
2. Ensure required packages are installed
3. Run all cells to reproduce the results

## 🚀 Future Work

- Test deep learning models for comparison
- Incorporate real-time data streaming
- Deploy the model using a web interface or API for medical use

## 🏆 Achievements

🥇 **1st Place – MEDNEXT ML Competition**  
Awarded for creating an effective machine learning solution for fetal heart rate monitoring and personalized risk assessment.

---

> **Author:** Sreeram Vishnu  
