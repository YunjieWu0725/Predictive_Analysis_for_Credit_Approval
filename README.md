# Credit Card Approval Prediction  
## A Credit Card Dataset for Machine Learning!  
### link
https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?datasetId=426827&sortBy=voteCount
### Context  
Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.  
 
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.  
 
At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

### Task
Build a machine learning model to predict if an applicant is 'good' or 'bad' client, different from other tasks, the definition of 'good' or 'bad' is not given. You should use some techique, such as vintage analysis to construct you label. Also, unbalance data problem is a big problem in this task.

### Table of Content
* 0. Reading the datasets
* 1. The information of the dataset
  * 1.1 Preprocess application record table
  * 1.2 Preprocess the credit record table
  * 1.3 Convert variables
  * 1.4 The cover rate of the application table on the credit record table
* 2. Feature Engineering
  * 2.1 Target Variable
    - Conversion Rate Analysis
    - Vintage Analysis
    - Denote the IDs
  * 2.2 Features
    - 2.2.1 Binary Variables  
      GENDER  
      CAR  
      REALITY  
      FLAG_WORK_PHONE  
      FLAG_PHONE  
      FLAG_EMAIL  
    - 2.2.2 Category Variables(non-binary)  
      NAME_INCOME_TYPE  
      NAME_EDUCATION_TYPE  
      NAME_FAMILY_STATUS  
      NAME_HOUSING_TYPE  
    - 2.2.3 Continuous Variables  
      CNT_CHILDREN  
      AMT_INCOME_TOTAL  
      DAYS_BIRTH  
      DAYS_EMPLOYED  
      CNT_FAM_MEMBERS  
    - 2.2.4 Summary
* 3. AR (Accept-Reject) credit model
  * 3.1 Logistic Regression
  * 3.2 SVM
  * 3.3 Decision Tree
  * 3.4 XGBoost
  * 3.5 Random Forest
  * 3.6 Summary
