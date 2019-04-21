# Heart Disease - Prediction
![image.png](Image1/heart3.png)

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
| Title| Analysis | Description |
| --- | --- | --- |
| Target and Sex Distribution | ![Image.png](image1/heart4.png) |
| Sex Type and Age is associated with Heart Disease | ![Image.png](image1/heart5.png) |
| What attributes Increases the occurrence of Heart Disease| ![Image.png](image1/heart6.png) |


[Jupyter Notebook](./HR_Analytics.ipynb)
