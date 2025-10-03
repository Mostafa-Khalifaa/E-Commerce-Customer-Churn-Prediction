# 📦 E-Commerce Customer Churn Prediction

## 📖 Project Overview
This project predicts **customer churn** in the E-Commerce domain using **machine learning** and **data visualization**.  
The full workflow includes:
- Data preprocessing (handling missing values and outliers)
- Different imputation techniques: **KNN, Regression, MICE**
- Feature selection using correlation analysis
- Model training and evaluation (Random Forest, Logistic Regression, Gradient Boosting)
- Business insights visualization with **Power BI**

The goal is to help businesses **reduce churn, improve customer retention, and make data-driven decisions**.

---

## 🛠️ Tools & Libraries
- **Python:** pandas, numpy, matplotlib, seaborn, scikit-learn, missingno  
- **Power BI:** Interactive dashboards and business insights  
- **Dataset:** [Kaggle - E-Commerce Customer Churn](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)  

---

## 📊 Models Implemented
- Logistic Regression  
- Random Forest (**Best performing model**)  
- Gradient Boosting  

---

## 📈 Results
- **Random Forest** achieved the highest Accuracy, Precision, Recall, and F1-score.  
- Power BI dashboards summarize:
  - Raw dataset quality
  - Missing values & outliers
  - Data after preprocessing
  - Model performance comparison  

---

## 🚀 How to Run
1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
   ```

2. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run analysis:**
   ```bash
   python code/churn_analysis.py
   ```

4. **Results:**
   - Cleaned datasets and metrics will be saved in the **results/** folder  
   - Open `visualizations/churn_dashboard.pbix` in **Power BI** to explore dashboards  

---

## 📂 Project Structure
```
Customer-Churn-Prediction/
│
├── code/                # Python code (preprocessing, training, evaluation)
├── data/                # Sample dataset or Kaggle link
├── visualizations/      # Power BI dashboard (.pbix)
├── report/              # Full PDF project report
├── results/             # Cleaned datasets and model results
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
