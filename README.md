[README.md](https://github.com/user-attachments/files/23738781/README.md)
# Credit Card Default Risk Analysis
### Predictive Modeling • Risk Analysis • Profit Optimization  

**Tools:** Python, Pandas, NumPy, Matplotlib, Scikit-Learn  
**Techniques:** Logistic Regression, Random Forest, EDA, ROC Analysis, Expected Loss Modeling, Profit Optimization

---

## 📌 Project Overview

This project builds a complete end-to-end **credit risk modeling pipeline** simulating how a bank predicts customer default and optimizes credit approval decisions. The workflow includes:

- Data cleaning and feature engineering  
- Exploratory data analysis (EDA)  
- Logistic Regression and Random Forest modeling  
- Probability of Default (PD) estimation  
- Expected Loss (EL) and profit modeling  
- Portfolio optimization using PD cutoff sweeps  
- Final recommended PD threshold for credit approval  

This project mirrors real-world credit risk practices used in banking and financial institutions.

---

## 📁 Repository Structure

```
Credit-Card-Default-Risk-Analysis/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── credit_risk_dataset.csv
│
├── notebooks/
│   └── Credit_Risk_Project_Notebook.ipynb
│
├── reports/
│   ├── Credit_Risk_Report.pdf
│   └── Credit_Risk_Presentation.pptx
│
└── src/
    ├── model_training.py
    ├── risk_calculation.py
    ├── optimization.py
    └── utils.py
```

---

## 🔍 Key Results

- Random Forest showed the strongest predictive power (higher ROC-AUC)  
- PD scores were generated for each account  
- Expected Loss (EL = PD × LGD × EAD) calculated for portfolio  
- Profit optimization identified the PD cutoff that maximizes lending profitability  
- EDA revealed strong behavioral signals like utilization and delinquency history  

---

## 📊 Example Outputs

- ROC curves (Logistic Regression vs Random Forest)  
- Feature importance chart  
- Default rate by utilization bands  
- Profit vs PD cutoff optimization graph  

(All outputs visible in the notebook.)

---

## 🧠 Skills Demonstrated

- Machine Learning (classification)  
- Financial Risk Modeling  
- Portfolio Optimization  
- Exploratory Data Analysis  
- Python data workflows  
- Visualization using Matplotlib  
- Interpretability (feature importance, score trends)

---

## ▶️ How to Run This Project

### **1. Clone the repo**
```bash
git clone https://github.com/yourusername/Credit-Card-Default-Risk-Analysis.git
cd Credit-Card-Default-Risk-Analysis
```

### **2. Install dependencies**
```bash
pip install -r requirements.txt
```

### **3. Launch the notebook**
```bash
jupyter notebook notebooks/Credit_Risk_Project_Notebook.ipynb
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
scikit-learn
jupyter
```

---

## 📜 License
MIT License (free to use, modify, and share)

---

## 👨‍💻 Author
**Ashraful Enam**  

---
