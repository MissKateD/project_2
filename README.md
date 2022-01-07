# Proposal - Predicting the possibility of a Heart Attack


## Overview 

[According to the CDC,](https://wonder.cdc.gov/controller/datarequest/D76;jsessionid=DE3EB5A7DC7D076CE0244F57CA26) from 1999 through 2020, the number one leading cause of death was diseases of the heart in the US. According to the data, some 600k+ of deaths during this period were from Heart Disease. Heart Disease while linked to an older demographic, can theoretically happen to someone of any age depending on a number of factors including Family history with Heart Disease, Diet and lack of physical exercise.

## Objective
Science has improved in determining what factors can lead to Heart Disease to help us improve factors we can control to live better lives. The aim of this project is to determine if we can use Machine Learning in order to determine if a person has a higher chance at suffering from Heart Disease. We will determine what the threshold is for the cumulative stats that determine the increased possibilty of Heart Disease using measurable statistics.


## About The Data
### Data Source
we will be using data sourced from [UC Irvine's Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). That data was created from the following contributors:

* Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
* University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
* University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
* V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

The Data set contains 76 attributes, however it suggests to use 14 of them. The suggested 14 UCI recommends to use aredescribed in the Data Dictionary below.

### Data Dictionary
The below data points are the 14 the UCI recommend and have been used within experiments with the Cleveland Clinic Foundation. They are listed by the number as they appear in the list of 76 attributes.


* 3 (age) - Age of Patient in Years
* 4 (sex) - Integer of Patient Sex
	* 1 = male
	* 2 = female
* 9 (cp) - Reported Chest Pain Type
* 10 (trestbps) - Resting Blood Pressure
* 12 (chol) - Cholestoral in mg/dl (Milligrams per Decilitre)
* 16 (fbs) - Fasting Blood Sugar > 120 mg/dl
* 19 (restecg) - Resting Electrocardiographic Results
	* Value 0: normal
	* Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
	* Value 2: showing probable or definite left ventricular hypertrophy
* 32 (thalach) - Maximum Heart rate Achieved
* 38 (exang) - Excercise Induced Angina (Chest Discomfort due to lack of Blood Flow, in this cae induced by exercise)
* 40 (oldpeak) - ST depression induced by exercise relative to rest
* 41 (slope) - Slope of the peak exercise ST segment
	* Value 1: upsloping
	* Value 2: flat
	* Value 3: downsloping
* 44 (ca) - Number of Major Vessels (0-3) colored by [flourosopy](https://www.hopkinsmedicine.org/health/treatment-tests-and-therapies/fluoroscopy-procedure#:~:text=Fluoroscopy%20is%20a%20study%20of,can%20be%20seen%20in%20detail.)
* 51 (thal)
	* 3 = normal
	* 6 = fixed defect
	* 7 = reversable defect
* 58 (num) - The predicted Attribute
