# Starbucks Statistical Promotion Analysis & Optimization
1. [Installation](#installation)
2. [Objective](#objective)
3. [File Descriptions](#file-descriptions)
4. [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

## Installation
The code was developed using Python 3.6.3. Necessary packages beyond the Python Standard Library are:
- numpy==1.12.1
- pandas==0.23.3
- scipy==1.2.1
- scikit-learn==0.19.1
- matplotlib==2.1.0

## Objective
In this project, an A/B test on customer promotion is analyzed. Predefined KPIs are statistically evaluated.

**KPIs:**
- Incremental Response Rate (IRR)
- Net Incremental Revenue (NIR)

After exploratory and statistical analysis, a classification model based on customers' features is fitted to the data in order to optimize future promotion strategy. The goal is to target the most promising customers regarding IRR & NIR.

More details on the questions of interest can be taken from the Jupyter Notebook introduction.

## File Descriptions
**Starbucks.ipynb**
- notebook containing a detailed description of the questions of interest
- statistical analysis & optimization model

**training.csv**
- [Starbucks](https://www.starbucks.com/) training dataset used in the notebook (the dataset has been used for assessments of data scientist job interviews at Starbucks in the past)

**test_results.py**
- test on optimization model provided on [Udacity](https://www.udacity.com/).

**Test.csv**
- [Starbucks](https://www.starbucks.com/) test dataset used in test_results.py

## Licensing, Authors, Acknowledgements
The data used in this project was kindly provided by [Starbucks](https://www.starbucks.com/) in cooperation with [Udacity](https://www.udacity.com/) in the [Udacity Data Science Nanodegree](https://www.udacity.com/school-of-data-science) program.
