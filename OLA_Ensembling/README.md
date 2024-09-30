# Driver Attrition Prediction

This project aims to predict whether a driver will leave the company based on various attributes. The dataset includes monthly information for a segment of drivers from 2019 and 2020.

## Features

The features used in this project are grouped as follows:

* **Demographics**: 
  * City
  * Age
  * Gender
* **Tenure Information**: 
  * Joining Date
  * Last Working Date
* **Performance Data**: 
  * Quarterly Ratings
  * Monthly Business Acquired
  * Driver Grade
  * Income

## Approach

The project follows these key steps and methodologies:

1. **Exploratory Data Analysis (EDA)**: 
   * Data exploration, pattern identification, and handling missing values.
   
2. **Modeling**: 
   * Multiple ensembling and boosting techniques were applied:
     * **Random Forest** (Ensemble Method)
     * **Gradient Boosting Decision Trees (GBDT)**
     * **XGBoost**
     * **LightGBM**
