
# Hospital Readmission Prediction
![Realtor Logo](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/header.jpeg?raw=true)
## Overview
This project seeks to create a model that classifies whether a patient is likely to be readmitted to the hospital within 30 days of discharge givin the health conditions. This information will help Hospitals to determine individual patients' risk of returning in the hospital in this time period.


## Business Problems
American hospitals spent over $41 billion on patients who got readmitted within 30 days of discharge. Being able to determine factors that lead to higher readmission in such patients, and correspondingly being able to predict which patients will get readmitted can help hospitals save millions of dollars while improving quality of care.

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
![Condition Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/condition_price.jpg?raw=true)
### Diabetic Encounter in the system during Diagnosis.
![Condition Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/condition_price.jpg?raw=true)
### Feature Importance based on Model
![Condition Vs Price](https://github.com/avithekkc/P2-King-County-Housing-Price-Prediction/blob/main/images/condition_price.jpg?raw=true)

##  Results
All the above plot shows that Location, Grade and Condition impact the most on the price. This makes sense as a house with good condition and having good grade ( Grading is based on the quality of workmanship and builds ) and A good location will always have High price.


##   Repository Structure
```
├── datasets                            <- data used for the analysis.
├── images                              <- All images used throughout the project.
├── data-cleaning.ipynb                 <- Cleaning of data to create final dataset.
├── eda-modelling.ipynb                 <- EDA and Modeling.
├── presentation.pdf                    <- PDF version of project presentation.
└── readme.md                           <- README file for Quick overview on project.
```
