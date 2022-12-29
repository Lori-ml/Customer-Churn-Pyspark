# Installation

 

Following libaries are needed to run the code: pyspark,seaborn, numpy, pandas. You may install them by running following command.

 

```bash

pip install "package_name"

```

 

## Project Description

 

This project analyses a fictitious digital music provider under name Sparkify. Data has been provided in .json format and analysis was completed via pyspark. Main objects of this project are: **1.** Understand the behavior of churned customers and compare it with the un-churned ones.  **2.** Predict when a customer will churn while at the same time avoiding unwanted effects caused by false negatives. To reach these goals project has been divided in following sections:

 

**1. Data Understanding:**

        

 - Categorical and continuous data are explored via different statistical methods

- Dataset has been checked for data related issues (missing data, outliers). 

- New featues have been derived based on raw data

 

**2. Data Exploration:**

 

- This section uses different charts to compare churned vs un-churned customers.

 

**3. Feature Engineering**


 

- Based on above exploration transforms the dataset so that can be used in classification models.
- New dataset is vectorized and scaled, ready for modeling.

**4. Modeling**
 
- Following models are applied in the dataset 1.Random Forest 2. Gradient Boosted Tree 3. Decision Tree 4. Support Vector Machine. 
- Above models are compared on f1-score and accuracy metrics.
- Best model (Random Forest) is later tuned via cross-validation technique.
- Feature importance for Random Forest has been printed.

## Files Description

 

_**Sparkify.ipynb**_ - all above stes can be found in this notebook.

 

 

## Results

 

A details description of this project and its results can be found in this [Medium post](https://medium.com/@_Florida/churn-butter-not-customers-5cbb23d640f):

 

## License

 

Data for this project was made available through [Udacity](https://www.udacity.com/)
