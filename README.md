# Tutorial 1: Data Preprocessing

## Overview
This tutorial is part of the ML for Data Analytics course.  
We perform data preprocessing on the *Medical Insurance Charges* dataset to prepare it for machine learning models.

### Why Preprocessing?
Even though the dataset is clean, preprocessing is necessary because:
- Models require numerical inputs, so categorical data must be encoded.
- Features like `age`, `bmi`, and `children` are on different scales, which can affect model performance.
- We need to split data into training and testing sets for proper evaluation.

## Dataset
- **Name**: Medical Cost Personal Dataset
- **Source**: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv)  
- **Description**: Contains demographic and health-related attributes like age, sex, BMI, children, smoker status, region, and insurance charges.

## Steps Performed
1. Load the dataset
2. Check for missing values
3. Separate features and target
4. Encode categorical columns
5. Scale numerical columns
6. Split into train-test sets

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Tutorial-1.ipynb

## Credits
Dataset sourced from: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets)  
Original dataset creator: *Stedy* (Machine Learning with R book resources)
