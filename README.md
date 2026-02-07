# 🔍 AML Transaction Risk Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![Focus](https://img.shields.io/badge/Focus-AML%20%7C%20Risk%20Analytics-orange.svg)
![License](https://img.shields.io/badge/License-Educational-lightgrey.svg)

---

## 📌 Project Overview

This project focuses on **Anti-Money Laundering (AML) transaction risk analysis** using data analytics and machine learning.

The key idea behind this project is simple:  
👉 **Money laundering transactions are designed to look normal.**

Instead of relying only on fixed rules (like large transaction amounts), this project analyses **behavioural patterns** such as payment method, cross-border activity, and foreign currency usage to identify higher-risk transactions.

---

## 🎯 Project Objectives

- Understand how laundering transactions differ from normal transactions  
- Identify high-risk transaction behaviours  
- Apply a risk-based, data-driven approach to AML monitoring  
- Support compliance-focused decision making  

---

## 📊 Dataset Description

The dataset represents transaction-level financial data with the following key features:

- Transaction amount  
- Payment method (cash, digital, card)  
- Cross-border indicator  
- Foreign exchange (FX) indicator  
- Laundering flag (target variable)  

> ⚠️ *Data used is anonymised / synthetic and for educational purposes only.*

## 📊 Dataset Source

The dataset used in this project was sourced from Kaggle.

Due to file size and licensing considerations, the dataset is not included in this repository.

You can download the dataset directly from Kaggle and place it in the `data/` folder before running the notebook.

---

## 🔍 Exploratory Data Analysis (EDA)

Key analyses performed include:

- Distribution of transaction amounts  
- Comparison between laundering and non-laundering transactions  
- Risk analysis by payment channel  
- Cross-border vs domestic transaction comparison  
- FX vs same-currency transaction risk  

📌 **Key finding:**  
Transaction size alone is not a reliable indicator of money laundering risk.

---

## 🧠 Modeling Approach

- Addressed class imbalance in the dataset  
- Selected relevant transaction-level features  
- Trained a machine learning model to generate **probability-based risk scores**  
- Focused on **risk ranking**, not just yes/no classification  

---

## 📈 Model Evaluation

- Evaluation focused on **high recall**, which is critical in AML  
- Threshold optimisation used to minimise missed suspicious activity  
- False positives are accepted to reduce false negatives  

> 💡 In AML, missing suspicious transactions is riskier than reviewing extra alerts.

---

## 🧾 Key Insights

✔ Cash transactions show the highest laundering risk  
✔ Cross-border transactions have nearly **4× higher risk** than domestic  
✔ FX transactions significantly amplify laundering risk  
✔ Combining multiple behavioural features improves detection  
✔ Risk-based approaches align better with real-world AML practices  

---

## 🏦 Business & Compliance Perspective

This project mirrors how AML compliance teams operate in real environments by:

- Prioritising high-risk transactions for investigation  
- Supporting explainable, data-driven decisions  
- Aligning with regulatory expectations for risk-based monitoring  

---

## 🔮 Future Improvements

- Customer profiling and segmentation  
- Transaction sequence and time-based analysis  
- Network and relationship analysis  
- Real-time risk scoring and monitoring  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook

---

## 📌 Disclaimer

This project is for **educational and demonstration purposes only** and does not represent a production-ready AML system.

---

⭐ If you found this project useful, feel free to star the repository!
