# Credit Scoring Model

## 🚀 Project Overview
The **Credit Scoring Model** predicts a person’s **creditworthiness** using Python, transforming raw financial data into actionable insights. This project helps identify potential credit risks and supports data-driven decision-making for lenders and financial institutions.  

Through a **Jupyter Notebook**, the project walks you through **data exploration, preprocessing, feature analysis, model building, and predictions**, turning complex datasets into clear, meaningful insights.

---

## ✨ Key Features
- Step-by-step **interactive workflow** in Jupyter Notebook  
- Insightful **data visualizations** to reveal trends and patterns  
- Predictive model for **credit risk assessment**  
- Clean, reusable, and well-documented Python code  
- Ideal for learning **financial modeling, data analysis, and predictive analytics**

---

## 📊 Project Workflow
1. **Introduction & Problem Statement** – Understanding the task and dataset  
2. **Dataset Overview** – Exploring the data features and structure  
3. **Data Preprocessing** – Handling missing values, encoding, and scaling  
4. **Exploratory Data Analysis (EDA)** – Visualizing distributions and correlations  
5. **Model Building** – Training and evaluating predictive models  
6. **Results & Insights** – Presenting predictions and key takeaways  
7. **Conclusion** – Summary of findings and next steps

---
## 📈 Model Performance

The following machine learning models were trained to predict creditworthiness:

| Model                 | Accuracy  | Precision | Recall   | F1-Score | ROC-AUC  |
|----------------------|-----------|-----------|----------|----------|----------|
| Logistic Regression  | 0.861     | 0.764     | 0.531    | 0.627    | 0.869    |
| Decision Tree        | 0.893     | 0.740     | 0.793    | 0.765    | 0.857    |
| Random Forest        | 0.932     | 0.950     | 0.731    | 0.826    | 0.938    |
| XGBoost              | 0.937     | 0.950     | 0.754    | 0.840    | 0.950    |


✅ **Best Model:** XGBoost – chosen for final predictions due to **highest accuracy (93.7%)** and **strong precision, recall, F1-score, and ROC-AUC**.


---

## 🔧 Hyperparameter Tuning


Hyperparameter tuning was performed using RandomizedSearchCV to optimize model performance. The XGBoost model with tuned parameters achieved an accuracy of 93.81%, precision of 96.45%, recall of 74.54%, F1-score of 84.09%, and ROC-AUC of 0.95, significantly outperforming the baseline models. This tuning improved the balance between precision and recall, leading to better overall classification results.


---



## 🛠 Technologies & Libraries
- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn for model building  
- XGBoost

---

## ⚡ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Adina-Abrar/Credit_Scoring_Model.git

