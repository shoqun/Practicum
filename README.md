# Customer Activity Analysis and Prediction Model

## Project Overview
This project aims to develop a predictive model that estimates the probability of decreased purchasing activity among customers of the online store *"One Click"*.  
The solution will help personalize marketing offers and retain regular customers.

## Business Goal
The company noticed a decline in customer activity and wants to prevent further loss by retaining current clients through data-driven personalized offers.

## Dataset Description
The analysis is based on four datasets:
- `market_file.csv` — customer profiles, website activity, and marketing communications.
- `market_money.csv` — revenue per customer.
- `market_time.csv` — time spent by each customer on the website.
- `money.csv` — seller profit from each customer over the last 3 months.

## Methodology
1. **Data Preprocessing**: missing values, outliers, and type correction.
2. **EDA**: target distribution, feature analysis, correlation analysis.
3. **Feature Engineering**: merging datasets and deriving new features.
4. **Modeling**: comparison of multiple classification models:
   - K-Nearest Neighbors
   - Decision Tree
   - Logistic Regression
   - Support Vector Classifier  
   Best model selected based on F1-score and validated using cross-validation.
5. **Model Interpretation**: SHAP values used to assess feature importance.
6. **Customer Segmentation**: based on behavior, purchase patterns, and risk of churn.
7. **Recommendations**: tailored retention strategies for each segment.

## Result
The best-performing model achieved a strong F1-score and revealed key drivers behind declining activity.  
Business insights were translated into concrete strategies to improve customer retention.

---

🧠 *Project completed as part of the Yandex Practicum Data Science program.*

