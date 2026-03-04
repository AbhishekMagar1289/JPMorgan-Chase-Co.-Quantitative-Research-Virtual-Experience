# JPMorgan-Chase-Co.-Quantitative-Research-Virtual-Experience
A comprehensive quantitative finance project completed as part of the JPMorgan Chase &amp; Co. Quantitative Research Virtual Experience Program on Forage.  This repository demonstrates applied quantitative modeling, financial valuation techniques, credit risk analytics, and data-driven decision frameworks similar to real-world quant research workflows.
📖 Overview

This project simulates the responsibilities of a Quantitative Research Analyst working in financial markets and risk management.

The work focuses on:

Time-series forecasting

Commodity storage contract valuation

Credit risk modeling (PD & Expected Loss)

Credit score segmentation & rating optimization

Data preprocessing and exploratory analysis

Each module reflects practical financial modeling techniques used in banking and investment institutions.

✅ Modules & Key Deliverables
🔹 1. Natural Gas Price Forecasting

Built a time-series forecasting model to estimate future natural gas prices using statistical methods.

Highlights:

Data preprocessing and trend analysis

Seasonality modeling

12-month forward forecast generation

Visualization of forecast curves

Reusable price estimation function

Business Relevance:
Supports pricing, hedging, and commodity risk management decisions.

🔹 2. Gas Storage Contract Valuation Model

Developed a valuation prototype to simulate commodity storage operations and compute profitability.

Model Features:

Injection and withdrawal scheduling

Storage capacity constraints

Operational cost modeling

Strategy-level NPV calculation

Scenario & sensitivity analysis

Business Relevance:
Demonstrates valuation logic applied in energy trading and structured commodity contracts.

🔹 3. Loan Default Prediction & Expected Loss Model

Built supervised machine learning models to estimate borrower Probability of Default (PD).

Implemented Models:

Logistic Regression

Random Forest Classifier

Evaluation Metrics:

AUC

Brier Score

Precision-Recall AUC

Expected Loss Formula:
EL = PD × EAD × (1 − Recovery Rate)

Business Relevance:
Supports portfolio risk monitoring, capital provisioning, and credit decision systems.

🔹 4. Credit Score Bucketing & Rating Optimization

Implemented quantization techniques to convert continuous credit scores into categorical risk ratings.

Approaches Used:

MSE-based bucketing

KMeans clustering

Dynamic programming for optimal segmentation

Log-likelihood maximization

Outputs:

Optimal bucket boundaries

Rating assignment (1 = Best Credit, 5 = Highest Risk)

Bucket-level Probability of Default

Exportable rating map

Business Relevance:
Enhances risk segmentation frameworks used in credit underwriting and portfolio analytics.

🛠 Tech Stack

Programming Language:

Python

Libraries:

Pandas

NumPy

Scikit-learn

Statsmodels

Matplotlib

Tools:

Jupyter Notebook

Git & GitHub

📂 Project Structure
JP_Morgan_Virtual_Experience/
│
├── data/
│   ├── Nat_Gas.csv
│   └── Loan_Data.csv
│
├── task_1_forecasting/
├── task_2_storage_pricing/
├── task_3_credit_risk/
├── task_4_score_bucketing/
│
└── results/
🚀 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/JP_Morgan_Virtual_Experience.git
cd JP_Morgan_Virtual_Experience

Install dependencies:

pip install pandas numpy scikit-learn matplotlib statsmodels

Open Jupyter Notebook and run the desired module.

📊 Skills Demonstrated

Quantitative Financial Modeling

Time-Series Forecasting

Risk Analytics & Credit Modeling

Machine Learning for Finance

Statistical Optimization

Data Visualization & Interpretation

📌 Disclaimer

This project was completed as part of a virtual experience program for educational and portfolio purposes only.
It is not affiliated with or endorsed by JPMorgan Chase & Co.

👤 Author

Abhishek Magar
Quantitative Finance & Business Analytics Enthusiast
