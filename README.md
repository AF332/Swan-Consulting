# Churn Prediction Project - Swan Teleco

## Project Overview
The Swan Teleco Churn Prediction Project aimed to analyse customer behavior and identify the factors influencing churn. By leveraging a detailed customer dataset, the project developed predictive insights to inform retention strategies. Deliverables included a ranked list of the top 500 customers most likely to churn, a comprehensive churn risk score for all customers, and actionable recommendations for retention efforts.

### Objectives:
1. **Customer Demographics Analysis**: Understand the characteristics of customers most likely to churn based on gender, age, family status, and services used.
2. **Retention Factor Identification**: Identify services and contract types that encourage customer retention.
3. **Churn Prediction**: Develop a model to predict churn likelihood for all customers.
4. **Retention Strategy**: Provide a targeted list of at-risk customers for outreach and recommendations for reducing churn rates.

## Notebooks Overview
The project utilised interactive Python notebooks to conduct data analysis and build predictive models. Each notebook focused on a specific aspect of the pipeline:

### 1. **EDA and Feature Engineering**
- Conducted exploratory data analysis to uncover trends and correlations within the dataset.
- Engineered features based on customer demographics, contract types, and service usage to enhance predictive power.
- Visualised key findings, such as:
  - Higher churn rates among senior citizens and customers without dependents or partners.
  - Correlation between contract types and churn, with month-to-month contracts showing the highest churn rates.

### 2. **Project 5 Balanced.ipynb**
- Built a balanced dataset to address class imbalance between churners and non-churners.
- Developed and trained a predictive model using logistic regression.
- Evaluated model performance to ensure reliable predictions.

### 3. **Top 500 Churners Identification**
- Ranked customers by churn risk using the trained predictive model.
- Generated a targeted list of the top 500 customers most likely to churn, focusing on senior citizens and customers with early-stage tenures.

### 4. **Retention Strategy Development**
- Identified key retention strategies:
  - Promote one-year and two-year contracts to reduce churn likelihood.
  - Incentivise sign-ups for online security and backup services, as these were strongly associated with retention.
  - Improve customer service interactions to address common churn reasons like competitor offers and poor support experiences.

## Tools and Libraries Used
- **Python**: Primary language for analysis and modeling.
- **Jupyter Notebooks**: Interactive environment for exploratory analysis and model development.
- **Libraries**:
  - `pandas` and `numpy`: Data manipulation and analysis.
  - `scikit-learn`: Model building and evaluation.
  - `matplotlib` and `seaborn`: Visualisation of trends and patterns.

## Deliverables
1. **Churn Risk Predictions**:
   - A full list of customers ranked by churn likelihood.
2. **Top 500 At-Risk Customers**:
   - Prioritized list of customers most likely to churn for targeted outreach.
3. **Retention Strategies**:
   - Recommendations to improve customer retention.
4. **Presentation Deck**:
   - Visual summary of findings and actionable insights for the retention team.

## Key Findings
1. **Customer Demographics**:
   - Senior citizens and customers without dependents or partners showed the highest churn rates.
2. **Service Impact**:
   - Online security and backup services were significant in reducing churn likelihood.
3. **Contract Influence**:
   - Month-to-month contracts had the highest churn rates, while longer-term contracts significantly reduced churn.
4. **Early-Stage Tenure**:
   - Customers with tenures under 5 months showed disproportionately high churn rates.

## Conclusion
This project successfully identified key factors influencing customer churn and provided actionable recommendations for Swan Teleco to reduce churn rates. By delivering predictive insights and targeted retention strategies, the project demonstrated the value of data-driven approaches in customer retention.
