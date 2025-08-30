## Healthcare Readmission Risk Prediction

## Problem Statement
Hospital readmissions within 30 days are a critical issue for healthcare providers.  
They increase treatment costs, reduce patient satisfaction, and signal gaps in care management.  
Hospitals need a reliable way to **identify patients at high risk of readmission** before discharge.  


## What I Did
- Processed and analyzed **100K+ hospital patient records**  
- Cleaned data, handled categorical encoding, and removed irrelevant variables  
- Balanced class distribution using **SMOTE** to address readmission rarity  
- Trained and compared multiple models (**Logistic Regression, Random Forest, Gradient Boosting**)  
- Evaluated performance with **Accuracy, ROC-AUC, Precision, Recall, and Confusion Matrix**  


## Key Findings
- **Medication changes** were a top driver of readmission risk  
- **Insulin usage patterns** strongly influenced likelihood of return  
- **Prior inpatient visits** significantly increased readmission probability  
- **High number of lab procedures** correlated with more complex/critical patients returning  
- **Older age groups (60+)** were more prone to readmission compared to younger patients  


## Results
- Best Model: **Random Forest Classifier**  
- Performance:  
  - **91% Accuracy**  
  - **0.90 ROC-AUC**  
  - **86% Recall** (captured most high-risk patients)  



## Decision-Making Impact
This project enables hospitals to:  
- **Identify at-risk patients before discharge**  
- Launch **targeted follow-up programs** (calls, home health visits) for high-risk patients  
- Improve **discharge planning** by focusing on patients with medication changes or prior admissions  
- Reduce **unnecessary readmissions**, lowering costs and improving patient outcomes



Dataset sourced from public hospital records (for educational purposes)

Inspired by real-world challenges in healthcare analytics and patient care
