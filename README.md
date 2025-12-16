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
#### Age Distribution
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Age_Distribution.png)

#### Income Distribution
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Income_Distribution.png)

#### Spending Distribution
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Spending_Distribution.png)

#### Education V/S Income
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Education_and_Income.png)

#### Marital Status V/S Total Spending
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Marital_Status_Total_Spending.png)

#### Correlation Heatmap
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Correlation_Matrix.png)

#### Average Spending By Education
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/b8ab0cfcd4c6bb6bfa92f4a94ec964376bf299c3/Images/Avg_Spending_Education.png)

## Dependencies
```bash
  pip install -r requirements.txt
```

## Demo
https://sundeepchaluvadi-customer-segmentation-proj-segmentation-uqun6r.streamlit.app/

## Installation
Clone the repository:

```bash
  ggit clone https://github.com/SundeepChaluvadi/Customer-Segmentation-Project.git
  cd Customer-Segmentation-Project
```

## Model Evaluation
#### Elbow Method
![image alt](https://github.com/SundeepChaluvadi/Credit-Risk-Modeling/blob/c9e4f342829b8ae110fefbac76c236ba695666f0/images/Confusion_matrix.png)

#### Visualizing Clusters Using PCA
![image alt](https://github.com/SundeepChaluvadi/Customer-Segmentation-Project/blob/4a1a72780f2919435e1ac6090e88665413de26a1/Images/Customer_Segmentation.png)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]([https://www.linkedin.com/](https://www.linkedin.com/in/sundeep-chaluvadi))

## Sources
[https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk](https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering)
