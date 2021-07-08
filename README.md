

# Hospital Readmission Prediction
![Realtor Logo](https://github.com/avithekkc/hospital-readmission-classification/blob/main/images/P3-Project.jpg?raw=true)
## Overview
This project seeks to create a model that classifies whether a patient is likely to be readmitted to the hospital within 30 days of discharge given the health conditions. This information will help Hospitals to determine individual patients' risk of returning in the hospital in this time period.


## Business Problems
Hospitals in USA spent over $41 billion on patients who got readmitted within 30 days of discharge. Being able to determine factors that lead to higher readmission in such patients, and correspondingly being able to predict which patients will get readmitted can help hospitals save millions of dollars while improving quality of care.

## Data
Data was obtained from [Kaggle ](https://www.kaggle.com/brandao/diabetes)

## OSMEN Process

 1. Obtaining data
 2. Scrubbing data
 3. Exploring data
 4. Modeling data
 5. Interpreting results

## FINDINGS
### Number Of Inpatient visits

It was found that if the patient had more Inpatients stays in hospital over a past year the probability of readmission within 30 days was higher.
![Condition Vs Price](https://github.com/avithekkc/hospital-readmission-classification/blob/main/images/number_inpatient.jpg?raw=true)
### Diabetic Encounter in the system during Diagnosis.

It was Found that the Patients that were encountered Diabetic during diagnosis had higher probability of readmission within 30 days.
The primary diagnosis is the root cause of the visit. The Secondary diagnosis/diagnoses, are the other conditions that were either present on admission & directly affect the care given for this visit
![Condition Vs Price](https://github.com/avithekkc/hospital-readmission-classification/blob/main/images/time_in_hospital.jpg?raw=true)
### Time In Hospital (Days between admission and discharge)

It was found that if the patient had spent more time in hospital ( considering serious illness ) the probability of readmission within 30 days was higher.
![Condition Vs Price](https://github.com/avithekkc/hospital-readmission-classification/blob/main/images/diag.jpg?raw=true)

##  Results
4 classification models were performed to determine best fit:
Logistic Regression, Decision Tree, Random Forest, and XGBoost.

The Random Forest Model is reported to be the best model for prediction of the Readmission of the patient with given medical information with an emphasis Recall in an effort to minimize false predictions of no readmittance.

RECALL : 63.00%

ACCURACY : 62.25%

AUC : 67.40%


##   Repository Structure
```
├── datasets                            <- data used for the analysis.
├── images                              <- All images used throughout the project.
├── data-cleaning.ipynb                 <- Cleaning of data to create final dataset.
├── modeling.ipynb                      <- EDA and Modeling.
├── presentation.pdf                    <- PDF version of project presentation.
└── readme.md                           <- README file for Quick overview on project.
```
