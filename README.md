# Advance-Project 3

# Profit Prediction Model

# Objective of Model
 Build a robust multiple linear regression model to predict profit for startups based on various features including R&D Spend, Administration, Marketing Spend, and State. The aim is to maximize prediction accuracy and gain insights into the key factors influencing profit, facilitating informed decision-making for business strategies.
 
## Dataset Overview
### Dataset
   Name: 50_startups data

   Columns: R&D Sp
   ,Administration
   , Marketing Spend
    , State
    , Profit
# Model Used
Algorithm: Multiple Linear Regression
# Methodology
### 1.Exploratory Data Analysis(EDA):

Explored relationships and distributions within the dataset.
Examined the correlation matrix to identify potential predictors of 'Profit'.
Visualized associations through pairplots and boxplots.


### 2. Data Preprocessing:

Checked for missing values and ensured data integrity.
Applied one-hot encoding to the categorical variable 'State'.
Prepared the dataset for model training.

### 3. Libraries Used:

pandas

numpy

matplotlib

seaborn

scikit-learn

### 4. Multiple Linear Regression Model:

#### Features Selected:
 'R&D Spend', 'Administration', 'Marketing Spend', 'State'.
#### Target Variable: 
'Profit'.
#### Model Training: 
Split the dataset into training and testing sets.
#### Training Algorithm: 
Utilized Multiple Linear Regression for predictive modeling.
### 5. Model Evaluation: 
Assessed the model's performance using the R^2 metric.


# Advance-Project 4
# Profit Prediction Model
### Project Overview:
 Multiple Linear Regression for Toyota Corolla Dataset.

# Model Objective

### Objective:
Build an effective multiple linear regression model to predict an profit based on various features such as Price, Age, KM, HP, cc, Doors, Gears, Quarterly_Tax, and Weight for Toyota Corolla cars. The goal is to optimize prediction accuracy and gain insights into the factors influencing the outcome.

# Dataset

Name: Toyota Corolla data

Columns:
Price- Offer preice in Euro

Age_08_04- Age in months

KM-  Accumulated Kilometer on odometer

HP- Horse Power

cc- cylinder volume in cubic centimeter

Doors- number of doors

Gears- number of gear position

Quarterly_Tax- Quaterly road tax in Euros

Weight- Weight in kilograms

# Methodology

### 1. Requirements:

Python 
Pandas
Scikit-learn
Matplotlib

### 2. Exploratory Data Analysis (EDA):

Explored the dataset's structure, summary statistics, and correlation.
Visualized relationships between selected numeric variables using pairplots.
Gained insights into potential predictors affecting the outcome.

### 3. Data Preprocessing:

Checked for missing values and ensured data integrity.
Performed any necessary transformations, such as handling missing values or encoding categorical variables.
Prepared the dataset for model training.

### 4. Multiple Linear Regression Model:

#### Features Selected:
 Price, Age_08_04, KM, HP, cc, Doors, Gears, Quarterly_Tax, Weight.
Target Variable: Profit

#### Model Training:
 Split the dataset into training and testing sets.

#### Training Algorithm: Utilized Multiple Linear Regression for predictive modeling.

### 5. Model Evaluation: 
Assessed the model's performance using the R^2 metric.
