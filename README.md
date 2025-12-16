# Credit Risk Modeling
Analyzed customer behavior patterns to identify meaningful segments that drive targeted marketing, improved retention, and higher sales.

## Business Problem
Businesses struggle to understand diverse customer behaviors, leading to ineffective marketing, lower retention, and missed revenue opportunities.

## Data Preprocessing
#### 1. Handling Missing Values
- Checked the dataset for missing values and removed rows with missing data to ensure a clean dataset for modeling.

#### 2. Changing the datatype of 'Dt_Customer' from object to datetime64[ns]

#### 3. Adding a column 'Age' using Year_of_Birth

#### 4. Adding a column 'Total_Children' by adding the values of Kidhome and Teenhome

#### 5. Calculating the total spending of each customer

#### 6. Calculating the Customer Tenure

## Data Visualization
#### Distributions of Sex, Job, Housing, Saving accounts, Checking account, Purpose
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/3de66133cbd6d3d83bfab5818abbab8d051a586b/images/Distributions.png)

#### High Correlation between Credit Amount and Duration
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/6a13e2a2c1fd0df6b6b188ea8a4676e5ff6196ae/images/Correlation.png)

#### Most of the credit is centered aroung young age with low credit amount <br> As the credit amount is increasing, larger dots implying more duration
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/816ce753b88c3b98cc5c27218dd3f70f0ee95800/images/Credit_Amt_By_Sex_and_Duration.png)

#### "Credit amount" and "Duration" affect "Risk" highly
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/816ce753b88c3b98cc5c27218dd3f70f0ee95800/images/Credit_amt_and_Duration_Risk.png)

## Dependencies
```bash
  pip install -r requirements.txt
```

## Demo
https://credit-risk-modeling-123.streamlit.app/

## Installation
Clone the repository:

```bash
  git clone https://github.com/SundeepChaluvadi/Credit-Risk-Modeling.git
  cd credit-risk-modeling
```

## Model Evaluation
#### Confusion Matrix
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/c9e4f342829b8ae110fefbac76c236ba695666f0/images/Confusion_matrix.png)

#### ROC-AUC Curve
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/c7c3c57d495087112a572613fb391bc67eea362f/images/Roc_Auc_Curve.png)

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]([https://www.linkedin.com/](https://www.linkedin.com/in/sundeep-chaluvadi))

## Sources
https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk
