# Homework 3: Random Forests  
**Author:** Zin Min Thant  
**Date:** 2024-10-27  

---

## Project Overview

This project builds a Random Forest model to predict individual credit scores using credit-related data. The model is trained using 5-fold cross-validation and used to predict the credit score of a new individual.

---

## Data

- **creditscore.csv:** Dataset containing features related to credit history and the target variable `CreditScore`.
- **new_individual_creditscore.csv:** New individual data used for prediction.

---

## Methodology

1. Load data into R.
2. Train a Random Forest model with 5-fold cross-validation and tune the `mtry` parameter.
3. Use the trained model to predict credit score for new individual data.
4. Output predicted score rounded to 0 decimal places.

---

## Results

- Predicted credit score for the new individual: ** 580.5117**

---

## Usage

1. Install required packages: `caret`, `rpart`, `rpart.plot`, `randomForest`.
2. Place the datasets (`creditscore.csv` and `new_individual_creditscore.csv`) in your working directory.
3. Run the R script or R Markdown file.
4. Review output and predictions.

---

## Contact

For questions, please contact Zin Min Thant.

