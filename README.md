 predective_customer_analysis
This project uses machine learning to predict customer purchase likelihood based on demographic and behavioral data.

## Features
- Random Forest Classifier (87%+ accuracy)
- Synthetic dataset with age, gender, income, and score
- Streamlit dashboard to interact with predictions

## How to Run
```bash
pip install -r requirements.txt
cd notebooks && python customer_behavior_model.py
cd ../dashboard && streamlit run dashboard_app.py
