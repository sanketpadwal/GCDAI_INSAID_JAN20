# **Heart Failure Clinical Records Data Set**
### *KNN Algorithm and Grid Search CV*

<center><img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Algorithms/KNN/Snap215.jpg?raw=true" width="1000" height="400" /></center>
*image source - https: //newatlas.com/medical/novel-ai-system-proves-100-accurate-at-detecting-heart-failure-from-a-single-heartbeat/*

## Problem Statement
Predict the probability of the heart failure instances based on age, gender, pre-existing health conditions, habbits and blood sample readings.

## Objective
 - Explore K-NearestNeighbour algorithm
 - Validate hyperparameters with Grid Search Cross Validation 

## About this dataset
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.
Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.
Most cardiovascular diseases can be prevented by addressing behavioral risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.
*data source - https://www.kaggle.com/andrewmvd/heart-failure-clinical-data

**Attribute Information:**

Thirteen (13) clinical features:

- age: age of the patient (years)
- anaemia: decrease of red blood cells or hemoglobin (boolean) 0 - no; 1 - yes
- high blood pressure: if the patient has hypertension (boolean) 0 - no; 1 - yes
- creatinine phosphokinase (CPK): level of the CPK enzyme in the blood (mcg/L) 
- diabetes: if the patient has diabetes (boolean) 0 - no; 1 - yes
- ejection fraction: percentage of blood leaving the heart at each contraction (percentage)
- platelets: platelets in the blood (kiloplatelets/mL)
- sex: woman or man (binary) 0 - female; 1 - male
- serum creatinine: level of serum creatinine in the blood (mg/dL)
- serum sodium: level of serum sodium in the blood (mEq/L)
- smoking: if the patient smokes or not (boolean) 0 - no; 1 - yes
- time: follow-up period (days)
- [target] death event: if the patient deceased during the follow-up period (boolean) 0 - survived; 1 - died
