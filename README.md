# 📡 *Customer Churn Prediction Using Machine Learning*

## 📘 Overview  
This project focuses on predicting customer churn for a telecom service using Machine Learning techniques.  
The dataset contains numerical customer behavior features, and the goal is to identify customers who are likely to leave the service.

This is a **Classification problem** with a strong emphasis on handling **class imbalance** and interpreting model performance beyond simple accuracy.

## 🧠 Project Highlights
- Type: Classification  
- Language: Python 🐍  
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn  
- Dataset: `customer_churn_dataset.csv` — numeric customer behavior data  

## ⚙️ Workflow
- Data Preprocessing – feature scaling and preparation using pipelines  
- EDA (Exploratory Data Analysis) – distribution analysis, outliers, and correlation inspection  
- Baseline Modeling – LR, LDA, KNN, NB, CART, SVM  
- Model Tuning – hyperparameter optimization using GridSearchCV  
- Imbalance Handling – applying SMOTE to address minority class underrepresentation  
- Model Evaluation – accuracy, confusion matrix, precision, recall, and F1-score  

## 🚧 Challenges
- Highly imbalanced target classes  
- Accuracy proved to be a misleading metric  
- Models initially favored the majority class and ignored churn cases  

## 📊 Results
✅ Best Performing Models: LDA & KNN  
🎯 Accuracy (Before SMOTE): ~90% (misleading due to imbalance)  
📉 Accuracy (After SMOTE): ~70% (more realistic and meaningful)  
🔥 Recall for Churn Class improved significantly after imbalance handling  

The final models prioritize identifying churn customers rather than maximizing accuracy alone.

## 💡 Skills Used
🐍 Python  
🤖 Machine Learning  
📊 Data Analysis  
⚖️ Imbalanced Classification  
📈 Model Evaluation & Tuning  
📉 Data Visualization  

## 📁 Files Included
- `customer_churn_analysis.ipynb` → Main analysis notebook  
- `customer_churn_dataset.csv` → Dataset  

## 📬 Contact
📧 amirhossin6825@gmail.com  
💬 Telegram: @AmirHossin6825
