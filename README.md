# Dataset of Heart Disease Patients' Symptoms

## Overview

This repository contains a comprehensive dataset of patient symptoms related to heart disease. The dataset is designed to be used for research and educational purposes, particularly in the field of machine learning and data analysis for heart disease prediction. The data was sourced from a well-known cardiology hospital and includes various health indicators.

## Dataset Description

The dataset includes the following features:

- **Age**: Age of the patient.
- **Sex**: Gender of the patient (1 = male; 0 = female).
- **Chest Pain Type**: Type of chest pain experienced (0 = typical angina; 1 = atypical angina; 2 = non-anginal pain; 3 = asymptomatic).
- **Resting Blood Pressure**: Resting blood pressure (in mm Hg).
- **Heartbeat Rate**: Resting heart rate (in beats per minute).
- **Fasting Blood Sugar**: Fasting blood sugar level (> 120 mg/dl, 1 = true; 0 = false).
- **Maximum Heart Rate**: Maximum heart rate achieved during exercise.
- **Exercise-Induced Angina**: Exercise-induced angina (1 = yes; 0 = no).
- **Target**: Diagnosis of heart disease (1 = heart disease; 0 = no heart disease).

## File Structure

- `Dataset.csv`: The main dataset file containing all the records and features.
- `README.md`: This README file providing an overview and details about the dataset.

## Usage

### Loading the Data

You can load the dataset into a Pandas DataFrame using the following code:

```python
import pandas as pd

# Load the dataset
heart_data = pd.read_csv('Dataset.csv')

# Display the first few rows of the dataset
print(heart_data.head())
```
## Contributing

If you wish to contribute to this repository, please fork the repository, create a new branch for your changes, and submit a pull request. Contributions are welcome!

## License

This dataset is shared under an open license. You are free to use it for research and educational purposes. Please cite the source when using the data in your publications.
