# Predicting-Company-Bankruptcy

This repository contains my coursework project, where I applied data analytics and machine learning to predict company bankruptcy. The project involved a data analytic report and an accompanying Jupyter notebook, which demonstrates the steps and methods used in this analysis.

## Project Overview

The main goal of this project is to predict whether a company will go bankrupt based on financial indicators and other relevant features. By analysing historical data, we aim to build predictive models that can accurately classify companies at risk of bankruptcy. 

The project deliverables include:
1. **Technical Report**: A detailed, structured report outlining the problem, data analysis, modeling process, and key findings.
2. **Jupyter Notebook**: A Python notebook containing all code implementations, visualizations, and results.

## Dataset

The dataset contains financial and operational indicators of various companies, labeled with whether they went bankrupt. The data was pre-processed and prepared for machine learning modeling.

- **Data Source**: https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction
- **Features**: Various financial indicators relevant to company performance and bankruptcy risk.
- **Target Variable**: Bankruptcy status (binary classification: bankrupt or not bankrupt).

## Methods and Techniques

To achieve reliable predictions, the following techniques and processes were applied:

1. **Data Preprocessing**: 
   - Applied **scaling** to standardize the features.
   - Used **SMOTE** (Synthetic Minority Over-sampling Technique) to address class imbalance.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed data distribution, checked for missing values, and visualised key relationships to gain insights into potential predictors of bankruptcy.

3. **Machine Learning Models**:
   - **Logistic Regression**: Chosen for its interpretability and ability to perform well in binary classification problems.
   - **Decision Tree**: Selected for its capacity to capture non-linear relationships and provide decision rules.

4. **Model Evaluation**:
   - **Cross-Validation**: Used cross-validation to assess model performance consistency.
   - **Confusion Matrix**: Analysed confusion matrices to understand model accuracy and error types.
   
## Key Findings

- **Model Performance**: Both Logistic Regression and Decision Tree models were compared, with performance assessed on accuracy, precision, recall, and other relevant metrics.
- **Feature Importance**: Decision trees helped identify important features, providing insights into the key indicators of bankruptcy risk.
- **Challenges**: Class imbalance in the dataset posed a challenge, addressed through SMOTE. Scaling was also crucial for model performance.

## Possible Extensions

Future work could include testing additional machine learning algorithms (e.g., Support Vector Machines, Random Forest) or applying ensemble techniques to further enhance model performance. Additionally, expanding the dataset or adding external data sources could improve model generalizability.
