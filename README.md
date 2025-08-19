# 🍴 Zomato Data Analysis & Restaurant Rating Prediction

## 📌 Project Overview
This project explores the Zomato dataset to analyze restaurant trends, customer preferences, and pricing patterns.  
It also builds **Machine Learning models** to predict restaurant ratings and provide insights for decision-making.  

The workflow includes:
- Exploratory Data Analysis (EDA) using the **UBM approach (Univariate, Bivariate, Multivariate)**  
- Feature Engineering & Data Preprocessing  
- Building & Evaluating ML Models (with Hyperparameter Optimization)  
- Visualizing results and comparing model performance  

---

---

## 🔍 Exploratory Data Analysis (EDA)
- **Univariate Analysis** → distribution of ratings, cost for two, cuisines  
- **Bivariate Analysis** → ratings vs cost, ratings vs cuisine type  
- **Multivariate Analysis** → combined effect of location, cost, and cuisine on ratings  
- Visualizations with **Matplotlib & Seaborn**  

---

## ⚙️ Feature Engineering & Preprocessing
- Handling **missing values**  
- Encoding categorical features (Label Encoding, One-Hot Encoding)  
- Normalizing numerical features  
- Feature selection based on correlation & importance  

---

## 🤖 Machine Learning Models
We implemented **3 ML models**:

1. **Logistic Regression** – baseline model  
2. **Random Forest Classifier** – improved performance with ensemble learning  
3. **XGBoost Classifier** – fine-tuned for best accuracy  

### 📊 Model Evaluation
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix, ROC-AUC Curve  
- Cross-validation results  

### 🔧 Hyperparameter Tuning
- **GridSearchCV**  
- **RandomizedSearchCV**  
- **Bayesian Optimization**  

---

## 📈 Results
- Logistic Regression: ~XX% accuracy  
- Random Forest: ~XX% accuracy  
- XGBoost: ~XX% accuracy (best performer ✅)  

📊 The XGBoost model outperformed others after hyperparameter optimization.  

---

## 🚀 Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, hyperopt  
- **Tools:** Jupyter Notebook / VS Code  

---

## ▶️ Quick Start
### 1. Clone the repo

git clone https://github.com/your-username/zomato-eda-ml.git
cd zomato-eda-ml

📌 Future Improvements
>Add Deep Learning model (ANN) for rating prediction

>Deploy as a Flask/Streamlit web app

>Expand dataset with more features
