# 🛒 Superstore Sales Analysis & Forecasting

## 📌 Problem Statement
The sales planning team relies on manual estimation for revenue forecasting.
This project builds a data-driven system to predict future sales using ML.

## 📊 Dataset
- Source: Superstore Sales Dataset
- Records: 9,800 rows, 18 columns
- Period: January 2018 – September 2018

## 🔧 Tools Used
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Power BI (Dashboard)

## 📈 Key Insights
- West region generates the highest sales
- Technology is the top-selling category
- Consumer segment contributes the most revenue
- Sales peak in Q3 months

## 🤖 ML Model Results
| Model | MAE | R2 Score |
|---|---|---|
| Linear Regression | 300.87 | 0.00 |
| Random Forest | 266.67 | 0.08 |
| Random Forest (after cleaning) | 67.58 | 0.27 |

## ✅ Conclusion
After removing outliers using IQR method, the Random Forest model improved
significantly with MAE dropping from 266 to 67.

<img width="1157" height="640" alt="Screenshot 2026-05-26 203548" src="https://github.com/user-attachments/assets/9fddc75e-4b15-40f7-8139-3f0314223c63" />

