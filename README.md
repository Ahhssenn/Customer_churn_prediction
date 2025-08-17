# Customer Churn Prediction

## 📌 Project Overview
This project analyzes customer churn in the telecom industry and builds predictive models to identify which customers are likely to leave the service. By understanding churn behavior, businesses can take proactive measures to retain customers and reduce revenue loss.

## 📂 Dataset
- **Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File used:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Target variable:** `Churn` (Yes/No)

## 🛠️ Techniques & Workflow
1. **Data Preprocessing**
   - Handling missing values (`TotalCharges` conversion & cleanup).
   - Dropping irrelevant features (`customerID`).
   - Encoding categorical variables (Label Encoding & One-Hot Encoding).
   - Feature scaling with `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**
   - Visualizations of customer demographics vs churn (e.g., gender, contract type, internet service).
   - Distribution plots for `tenure`, `MonthlyCharges`, and `TotalCharges`.
   - Correlation heatmap to identify key drivers of churn.

3. **Modeling**
   - Machine Learning models applied:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree Classifier
     - Random Forest Classifier
     - K-Nearest Neighbors (KNN)
   - Hyperparameter tuning using `GridSearchCV`.

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix Visualization

## 📊 Results
- Multiple models were compared based on accuracy and F1-score.
- Best performing models: **Random Forest** and **Logistic Regression** (after hyperparameter tuning).
- Final results and metrics are saved in `model_results2.txt`.

## 🚀 How to Run
1. Clone this repository:
   ```python
   git clone https://github.com/Ahhssenn/ml_project.git
   ```
2. Install dependencies:
  ```python
  pip install -r requirements.txt
  ```
## Links
Github repo [customer_churn_prediction](https://github.com/Ahhssenn/ml_project)\
Author: Mian Ahsan Jan
