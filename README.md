# Medical Insurance Cost Analysis

## Project Overview

This project analyses the factors associated with medical insurance charges using a publicly available dataset from Kaggle. Using Python in Jupyter Notebook, the project performs data cleaning, exploratory data analysis (EDA), statistical analysis and data visualisation.

The analysis focuses on understanding how demographic and lifestyle factors, particularly smoking status, are associated with differences in medical insurance charges.

---

# Objectives

* Explore the relationship between demographic factors and medical insurance charges
* Investigate how smoking status is associated with insurance costs
* Compare insurance charges between smokers and non-smokers
* Apply statistical methods to examine differences in average insurance charges
* Use Python for data analysis, statistical testing and visualisation

---

# Dataset Source

### Medical Cost Personal Dataset

Source: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

The dataset contains **1,338 records** and 7 variables related to individual medical insurance charges.

Variables include:

* Age
* Sex
* BMI (Body Mass Index)
* Number of Children
* Smoking Status
* Region
* Insurance Charges

After data cleaning and duplicate removal, **1,337 records** were used for analysis.

---

# Technologies & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# Project Workflow

## 1. Data Loading & Cleaning

* Imported the medical insurance dataset
* Inspected the dataset structure and data types
* Checked for missing values and duplicate records
* Removed duplicate records
* Prepared the cleaned dataset for analysis

## 2. Exploratory Data Analysis (EDA)

* Analysed the distribution of medical insurance charges
* Examined relationships between insurance charges and demographic factors
* Compared insurance charges between smokers and non-smokers
* Visualised patterns and differences using charts

## 3. Statistical Analysis

Applied statistical methods to investigate the difference in insurance charges between smokers and non-smokers:

* Used bootstrap resampling to estimate the confidence interval for the difference in average insurance charges
* Conducted permutation hypothesis testing using 10,000 resamples
* Evaluated whether the observed difference was statistically significant

## 4. Data Visualisation

Generated charts and statistical visualisations including:

* Distribution of medical insurance charges
* Comparison of insurance charges between smokers and non-smokers
* Relationships between demographic factors and insurance charges
* Visualisation of statistical analysis results

---

# Key Findings

## 1. Smoking Status Is Strongly Associated with Higher Insurance Charges

The analysis found a substantial difference in average insurance charges between smokers and non-smokers.

* Average charges for smokers: approximately **$32,050**
* Average charges for non-smokers: approximately **$8,441**
* Difference in average charges: approximately **$23,610**

This suggests that smoking status is strongly associated with higher medical insurance charges in the dataset.

## 2. Statistical Testing Supports the Observed Difference

Bootstrap confidence interval estimation and permutation hypothesis testing were used to investigate the difference between the two groups.

* The estimated 95% bootstrap confidence interval for the difference was approximately $22,199 to $25,020.
* The permutation test produced a very small p-value, providing strong statistical evidence of a difference in average insurance charges between smokers and non-smokers.

## 3. Other Factors Also Show Relationships with Insurance Charges

The analysis also explored other demographic factors:

* Age showed a positive relationship with insurance charges.
* BMI showed a weaker positive relationship with insurance charges.
* Number of children showed little relationship with insurance charges.

These findings suggest that different demographic and lifestyle factors may be associated with variations in medical insurance costs.

---

# Skills Demonstrated

* Data Cleaning
* Data Analysis
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Bootstrap Resampling
* Permutation Hypothesis Testing
* Confidence Interval Estimation
* Data Visualisation
* Python Programming
* Real-world Dataset Handling
* Problem Solving

---

# Project Structure

```text
├── TDDM_Project.ipynb
├── TDDM_Presentation_Final.pptx
├── README.md
```

---

# Notes

The dataset was obtained from Kaggle and contains publicly available medical insurance data.

This project is intended for educational and statistical analysis purposes. The findings describe associations within the dataset and do not establish that any particular factor directly causes higher insurance charges.

The dataset represents a sample of medical insurance records and may not reflect the pricing practices of all insurance providers or healthcare systems.

---

# How to Run the Project

1. Clone or download the repository.
2. Open the Jupyter Notebook file.
3. Ensure the required Python libraries are installed.
4. Make sure the dataset is available in the expected file location.
5. Run all notebook cells sequentially.

Required libraries:

```python
pip install pandas numpy matplotlib seaborn
```

---

# Author

Singapore Polytechnic – Diploma in Information Technology Student

Specialisation: Cloud Computing & Cybersecurity

Minor in Data & AI

Yip Jun Yi
