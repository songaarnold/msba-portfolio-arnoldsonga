Business Problem Summary
Customer churn directly threatens TruSource’s revenue stability and long-term growth. Acquiring new customers is significantly more expensive than retaining existing ones, so the business challenge is not only predicting who will churn, but identifying early warning signals that allow the company to intervene before customers leave.

The goal of this case competition was to use data-driven insights to understand why customers leave and recommend interventions that reduce churn while improving customer lifetime value.

Key Results

Identified the top churn drivers using machine learning and exploratory analysis.
Built a predictive model that accurately classified high‑risk customers.
Recommended targeted retention strategies projected to reduce churn meaningfully.

#How to replicate the code

**Install Dependencies:** Ensure you have Python installed, then run:  
   pip install pandas xgboost scikit-learn joblib matplotlib seaborn  
**Perform  preprocessing, data cleaning and feature engineering on the data set 
**Run Model Training:** Open and execute XGBOOST MODEL .ipynb to see the full pipeline from EDA to model evaluation.  
**Generate Predictions:** Use SCORED HOLDOUT CODES.ipynb to apply the saved model bundle to new holdout data.
**Output:** The final predictions will be saved as group8\_holdout\_scored.csv in the root directory.

Limitation / Risk
The model may rely on historical patterns that no longer reflect current customer behavior, which can reduce accuracy if business conditions change.