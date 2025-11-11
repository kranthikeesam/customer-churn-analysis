# Customer Churn Analysis – Telecom

This project predicts customer churn using the IBM Telco dataset (~7,000 customers).  
It combines **Python, Pandas, Seaborn, and Scikit-Learn** to clean, visualize, and model data.

## Key Insights
- Month-to-month contract holders are the most likely to churn.
- Longer tenure and automatic payments reduce churn risk.
- Higher monthly charges correlate with churn.

## Models and Performance
| Model | Accuracy | ROC-AUC |
|-------|-----------|---------|
| Logistic Regression | 0.80 | 0.84 |
| Random Forest | 0.79 | 0.82 |

## Tools Used
Python 3 • Pandas • NumPy • Matplotlib • Seaborn • Scikit-Learn  
Notebook: `customer_churn_analysis.ipynb`

## How to Run
1. Install Python 3.
2. Install libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

