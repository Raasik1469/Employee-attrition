# Heart Disease - Prediction
![image.png](Image1/beating-heart--ecg-graph.jpg)

## INTRODUCTION
Database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The __"goal"__ field refers to the presence of heart disease in the patient. It is integer valued from __0 (no presence) to 1(presence)__.


## DATA
| Column Name | Description |
| --- | --- |
| `AGE` | Numerical Value |
| `SEX` | Employee leaving the Company (0=no, 1=yes) |
| `CHEST PAIN TYPE`| (0= No Pain, 1= typical angina, 2= atypical angina, 3= non-anginal pain)|
| `RESTING BLOOD PRESSURE` | in mm Hg on admission to the hospital|
| `CHOL` | serum cholestoral in mg/dl |
| `FBS` | ((fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) |
| `RESTECG` | resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria 20 ekgmo |
| `THALACH` | Maximum heart rate achieved |
| `EXANG` | Exercise induced angina (1 = yes; 0 = no) |
| `OLDPEAK` | ST depression induced by exercise relative to rest |
| `SLOPE` | The slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping |
| `CA` | number of major vessels (0-3) colored by flourosopy |
| `THAL` | thalassemia-- 3 = normal; 6 = fixed defect; 7 = reversable defect |


## PROJECT ANALYSIS
| Title| Analysis |
| ---| --- | 
| Target and Sex Distribution | ![image.png](Image1/heart1.PNG) |
| Sex Type and Age is associated with Heart Disease | ![image.png](Image1/heart4.png) |
| What attributes Increases the occurrence of Heart Disease 1 | ![image.png](Image1/heart5.png) ![image.png](Image1/heart6.png) |
| How attributes are associated with distribution of ages | ![image.png](Image1/heart7.png) ![image.png](Image1/heart8.png) 


## ACCURACY OF MODELS
![image.png](Image1/heart9.png)

## CONFUSION MATRIX FOR MODELS
![image.png](Image1/heart11.png)

## AUC_ROC CURVE
![image.png](Image1/heart12.png)

## CONCLUSION
This dataset seems to be small by today's standards. However, it has allowed us to create a simple model and then use various machine learning explain ability tools and techniques to peek inside. 
Most of Attributes were good factors in the model. However each attribute can be analysed in depth to find out what really causes heart disease!
Machine learning has a greater and greater role in health care.

## CLICK TO VIEW FULL CODING  
      |
      |
     \|/
[Jupyter Notebook](./Heart_Disease_Project_2.ipynb)
