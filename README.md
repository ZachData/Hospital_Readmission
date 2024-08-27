## Overview

In this analysis, we explore Kaggle's hospital readmission data to identify the key factors predicting patient readmission. The dataset includes the following columns: `age`, `time_in_hospital`, `n_lab_procedures`, `n_procedures`, `n_medications`, `n_outpatient`, `n_inpatient`, `n_emergency`, `medical_specialty`, `diag_1`, `diag_2`, `diag_3`, `glucose_test`, `A1Ctest`, `change`, `diabetes_med`, and `readmitted`. Our goal is to determine which variables are most indicative of a patient being readmitted to the hospital.

## Methodology

### Exploratory Data Analysis

We conducted an Exploratory Data Analysis (EDA) to understand the dataset's structure and characteristics. Categorical data was analyzed by examining frequency distributions and relationships between categories, while numerical data was normalized and compared to readmission variables. This approach allowed us to assess how different features relate to readmission and to identify patterns and anomalies.

### Visualization

We created various visualizations to provide a clearer understanding of the data and the factors influencing readmission. By plotting different features against the readmission variable, we gained insights into which aspects of the data are most relevant to predicting patient outcomes.

## Key Findings

Our analysis revealed that the most significant factors affecting readmission include `age`, `n_lab_procedures`, and the categorical diagnoses of diabetes observed on multiple occasions. We used averaging and normalization techniques to ensure that the data was comparable across different scales and distributions.

## Visualizations

- [im1.png](link_to_image1) 
- [im2.png](link_to_image2) 
- [im3.png](link_to_image3)

## Conclusion

Our analysis highlights that certain data columns are particularly useful in predicting hospital readmission. By focusing on factors such as age, laboratory procedures, and diabetes diagnoses, we can better understand and anticipate patient readmission risks. This insight is crucial for improving hospital resource management and patient care strategies.

