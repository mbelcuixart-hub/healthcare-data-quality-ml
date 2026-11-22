
# Healthcare Data Quality & Machine Learning

## Project Overview

This project explores data quality and machine
learning methodologies using a healthcare dataset
containing symptom-based diagnostic categories.

The analysis focuses on identifying data quality
issues, assessing potential data leakage, and
evaluating the reliability of predictive results.

## Project Objectives

- Explore the structure and quality of healthcare data
- Identify duplicate observations
- Assess potential data leakage
- Apply data preprocessing techniques
- Train and evaluate a machine learning model
- Compare validation strategies
- Interpret results and methodological limitations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Methodology

The project includes exploratory data analysis,
duplicate detection, data preprocessing, and
machine learning model evaluation.

A stratified train-test split was applied after
deduplication to reduce exact record overlap
between training and testing datasets.

## Key Findings

The analysis highlights how duplicated observations
and dataset characteristics can influence machine
learning performance.

High predictive accuracy does not necessarily
indicate strong generalization to unseen patients,
particularly when training and testing records overlap.

## Limitations

- Limited number of unique observations per diagnosis
- Potential biases in the original dataset
- Limited clinical information
- No independent external validation
- No demonstrated clinical utility

## Skills Demonstrated

- Healthcare Data Analysis
- Data Quality Assessment
- Duplicate Detection
- Data Preprocessing
- Machine Learning Fundamentals
- Model Evaluation
- Data Leakage Assessment
- Scientific Interpretation

## Dataset Source

Dataset obtained from Kaggle.

**Dataset:** [Add dataset name and link]

**Author:** [Add dataset creator]

Please refer to the original dataset page for
licensing and usage conditions.

## Disclaimer

This project is intended for educational and
research purposes only.

The model is not validated for clinical diagnosis
or medical decision-making.

