# diabetes_logistic_regression / Diabetes Classification Project

## Overview

This project develops a classification model to predict the likelihood of diabetes based on various health indicators. The model utilizes a dataset containing information about age, BMI, blood pressure, and other relevant factors to assess diabetes risk. The goal is to provide a simple and understandable tool for identifying individuals who may be at risk and should seek further medical evaluation.

## Dataset

The dataset used in this project is `diabetes_dataset.csv`, which includes the following features:

*   **Age:** Age of the patient.
*   **Pregnancies:** Number of pregnancies.
*   **BMI:** Body Mass Index.
*   **Glucose:** Glucose level in the blood.
*   **BloodPressure:** Blood pressure reading.
*   **HbA1c:** Hemoglobin A1c level.
*   **LDL:** Low-density lipoprotein cholesterol level.
*   **HDL:** High-density lipoprotein cholesterol level.
*   **Triglycerides:** Triglyceride level.
*   **WaistCircumference:** Waist circumference measurement.
*   **HipCircumference:** Hip circumference measurement.
*   **WHR:** Waist-to-hip ratio.
*   **FamilyHistory:** Whether there is a family history of diabetes (0 or 1).
*   **DietType:** Type of diet followed by the patient.
*   **Hypertension:** Whether the patient has hypertension (0 or 1).
*   **MedicationUse:** Whether the patient is currently using any medication (0 or 1).
*   **Outcome:** Indicates whether the patient has diabetes (0 for no, 1 for yes).

The dataset was obtained from \[*Specify the source of your data if available.  If it's synthetic or from a competition, mention that.*]

## Project Structure

*   `diabetes_classification.ipynb` (or whatever name you chose): Jupyter Notebook containing the code for data loading, preprocessing, model training, and evaluation.
*   `diabetes_dataset.csv`: The dataset used for training and testing the model.
*   `README.md`: This file, providing an overview of the project.

## Dependencies

The following Python libraries are required to run the code:

*   pandas
*   numpy
*   scikit-learn (sklearn)
*   matplotlib
*   seaborn

You can install these libraries using pip:

