![Future-Crime-Analysis](https://github.com/user-attachments/assets/bc22a55d-5aaf-4a46-bf53-6931fbfc06b5)

# IBA Project: Crime Analysis & Prediction

This repository contains an analysis of the UCI ML Repository's **Communities and Crime** dataset, performed as part of the **Introduction to Business Analytics** course (BMS). The project involves data cleaning, exploratory data analysis (EDA), and regression modeling to identify significant factors contributing to crime rates and predict crime rates for regions.

---

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Analysis Steps](#analysis-steps)
4. [Results](#results)
5. [Usage](#usage)
   
---

## Overview
This project aims to:
- Analyze and understand significant contributors to the crime rate.
- Predict crime rates in communities based on socio-economic and demographic factors.
- Use linear and logistic regression techniques to model the dataset.

### Deliverables:
- Insights into the dataset through EDA.
- A predictive model evaluating crime rates.
- Data pre-processing steps for regression suitability.

---

## Dataset
The dataset used is the **Communities and Crime** dataset from the UCI ML Repository. 

- **Filename:** `communitiesNcrime-USA.csv`
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/communities+and+crime)
- **Description:** The dataset includes socio-economic, law enforcement, and demographic data for communities in the United States, alongside crime rates.

---

## Analysis Steps
1. **Load the Dataset**:
   - Imported from the CSV file.
   - Summary statistics reviewed.

2. **Data Cleaning**:
   - Handled missing values.
   - Removed features with excessive missing data.
   - Standardized data for regression.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features and crime rates.
   - Identified patterns and key features.

4. **Regression Modeling**:
   - **Linear Regression**:
     - Modeled continuous crime rates based on features.
   - **Logistic Regression**:
     - Converted the crime rate into binary classification (e.g., high/low) for logistic analysis.

5. **Evaluation**:
   - Analyzed model performance metrics (e.g., accuracy, R-squared, confusion matrix).

---

## Results
- **Key Insights from EDA**:
  - Socio-economic factors do significantly influence crime rates.

- **Model Performance**:
  - Linear regression achieved an R-squared of `47%`.
  - Logistic regression accuracy: `80%` on the test set.

---

## Usage
To run the analysis:
1. Clone the repository:
   ```bash
   git clone https://github.com/asvcodes/CrimePred
   ```
2. Ensure the `communitiesNcrime-USA.csv` file is in the `data/` folder.
3. Open and execute the `Crime_Analysis.ipynb` notebook using Jupyter.
4. Explore

Dependencies are listed in the `requirements.txt` file and can be installed with:
```bash
pip install -r requirements.txt
```

---
