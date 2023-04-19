### Diabetes-Classification-Modeling
#### Logistic Regression, Random Forest 


  Mohammad Ahmadi

  Business Inteligence Systems Infrastructure (BISI), Algonquin college

  Ottawa, ON, Canada
  
  ahma0205@algonquinlive.com


### Background 

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years.

The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians).

In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database.
 
In particular, all patients were females at least 21 years old of Pima Indian heritage. 

Here, we are analyzing different aspects of Diabetes in the Pima Indians tribe by doing Exploratory Data Analysis and building a classification Model.


### Data Set

- Dataset is a CSV file contain 9000 records for 36 KB in total contain 7 Integer variables and 2 Float

### Associated tasks

- Exploratory data analysis

Checking data types, distributions, corelations through visualization, statistical analysis 
	
- Data cleaning and feature engineering:
  
Checking for outliers, corelation matrix for droping posible high corelated variables

- Modeling
  
Rescaling the features and Splitting the data set into training and test sets
    
Training Logistic Regression model for classification of our target value 
    
Training Random forest for classification of our target value 
    
- Model Evaluation
  
Evaluation of models and comparing the items of the performance of each model

### Files

- Readme.txt
- diabetes.csv: 1000 rows and 9 columns. Records: 9000
- Mohammad_41109627.ipynb -classification modeling codes

	
 ### Dataset characteristics

diabetes.csv have the following fields:
	
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- Blood pressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skinfold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml) test
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: A function that scores likelihood of diabetes based on family history
- Age: Age in years
- Outcome: Class variable (0: the person is not diabetic or 1: the person is diabetic)
