# Predicting Heart Disease

The goal of this project is to explore the available CardioVascular Disease dataset (kaggle and UCI) and 
use machine learning to predict whether a person is having a cardiovascular disease. 

## DataSet Distribution

### Cleveland Clinic datasets

This dataset dates from 1988 and consists of four databases:
Cleveland, Hungary, Switzerland, and Long Beach V. 
It contains 76 attributes, including the predicted attribute, 
but all published experiments refer to using a subset of 14 of them. 
The "target" field refers to the presence of heart disease in the patient. 
It is integer valued 0 = no disease and 1 = disease.

THe 14 attributes are:
1. age
2. sex
3. chest pain type (4 values)
4.  resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
14. severerity of heart disease (angiographic disease status) 
    0: absent, 1-4 levels of disease 

Source: [UCI Cleveland Heart Disease](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)


### Kaggle datasets
he Kaggle cardiovascular disease dataset is an open-source dataset consisting of 70,000 
patient records (34,979 presenting with cardiovascular disease and 35,021 not presenting with cardiovascular disease) 
There are 11 features (4 demographic, 4 examination, and 3 social history):

Age | Objective Feature | age | int (days)
Height | Objective Feature | height | int (cm) |
Weight | Objective Feature | weight | float (kg) |
Gender | Objective Feature | gender | categorical code |
Systolic blood pressure | Examination Feature | ap_hi | int |
Diastolic blood pressure | Examination Feature | ap_lo | int |
Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
Smoking | Subjective Feature | smoke | binary |
Alcohol intake | Subjective Feature | alco | binary |
Physical activity | Subjective Feature | active | binary |
Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

Some features are numerical, others are assigned categorical codes, and others are binary values. The classes are balanced, but there were more female patients observed than male patients. Further, the continuous-valued features are almost normally distributed; however, most categorical-valued features are skewed towards "normal," as opposed to "high" levels of potentially pathological features.

Source: [https://www.kaggle.com/sulianova/cardiovascular-disease-dataset]

## Analysis

The analysis will be broken up into two sections. 
The first section will use exploratory data analysis (EDA) to gain insights 
into the dataset, discover any structures within,
extract variables that are important, detect any outliers or anomalies, 
and determine attributes should be used for the classification model. 

### Exploratory Data Analysis (EDA)

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Barchart.png "Logo Title Text 1")

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Pairplot.png "Logo Title Text 1")

## Classification


### Decision Tree

The second section will utilize a Decision Tree, which is a classification algorithm of supervised learning. The Decision Tree will use a two-step process which involves learning and predicting whether a patient has heart disease or not. 

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Decisiontree.png "Logo Title Text 1")

### K-Nearest Neighbors (KNN)

The third section will utilize a K-Nearest Neighbors (KNN), 
which is a classification algorithm of supervised learning.


### Artificial Neural Networks(ANN)


### Boosting


## Packages
  * Pandas (data structures and data analysis)
  * Seaborn (data visualization)
  * Matplotlib (data visualization)
  * Numpy (computing)
  * Scikit-learn (data mining and data analysis)
  
# heart
