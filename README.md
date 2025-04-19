# ☎️📺 Customer Churn Prediction - Telco Dataset

## 🧠 Overview
A predictive modeling project using real-world telecom data to identify customers at high risk of churning. Includes sentiment analysis and a recall-optimized classification model.

## ❓ Problem Statement
Customer churn is expensive. This project focuses on understanding customer behavior to proactively reduce churn and improve retention.

## 🔍 Approach & Methodology
- EDA using Snowflake SQL to identify behavioral patterns
- Feature engineering from contract length, services used, and complaints
- Applied NLP using NLTK for sentiment analysis from customer feedback
- Trained and tuned an XGBoost model with class imbalance correction
- Prioritized recall to reduce false negatives (missed churners)

## 🧰 Tools & Technologies
- Python (XGBoost, Plotly, NLTK, Imblearn), SQL (Snowflake), Pandas

## 📈 Results
- Achieved **high recall for churn prediction**
- Identified top churn indicators (e.g., contract type, monthly charges)
- Integrated sentiment analysis for customer feedback context

## 💡 What I Learned
- Combining structured data and unstructured text in ML workflows
- Advanced XGBoost tuning for business-critical use cases
- Effective model interpretation techniques for stakeholder reporting

## 🚀 Next Steps
- Convert to Streamlit dashboard for interactive retention planning
- Implement SHAP for model interpretability
 ![output](https://github.com/user-attachments/assets/b050d8e1-f7fd-456d-8174-0c1ce366d415)
 ![image](https://github.com/user-attachments/assets/0a2f098a-0f5e-4bf5-8c56-c7e33a05f3cb)
