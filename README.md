# Gym-membership
# Gym Behavior Analytics: Predictive Amenity Utilization
**Author:** Bashudev Saha  
**Student ID:** 24142631  
**Technical Repository:** [https://github.com/Bashudev-Saha/Gym-Analytics](https://github.com/Bashudev-Saha/Gym-Analytics)

## Project Overview
This repository contains a behavioral analytics pipeline designed to predict member engagement within fitness facilities. Using a dataset of 1,000 gym members, we implement a **Logistic Regression** model to forecast the likelihood of a member utilizing premium amenities, such as the **sauna**, based on their demographics and gym habits.



## Key Features
* **Feature Engineering:** Encoding of categorical variables (Gender, Subscription Type) and normalization of session metrics.
* **Explainable AI:** Use of logit coefficients to determine which behaviors (e.g., personal training or visit frequency) most impact amenity use.
* **Performance Metrics:** Evaluation through Confusion Matrices and Precision-Recall Area Under the Curve (AUC-PR).

## Repository Structure
* `gym_membership.csv`: Core dataset containing member demographics and habits.
* `behavioral_analysis.ipynb`: Complete Python implementation and visualization code.
* `images/`: Directory containing generated diagnostic plots.

## Installation
```bash
pip install pandas scikit-learn seaborn matplotlib
