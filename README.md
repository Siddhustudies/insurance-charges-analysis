# Insurance Charges Analysis 📊

A beginner data analysis project using Python to investigate factors associated with medical insurance charges.

## Project Overview

In this project, I used an insurance dataset to explore how different factors relate to insurance charges.

The analysis focuses on:

1. Understanding the structure of the dataset
2. Comparing insurance charges between smokers and non-smokers
3. Exploring the relationship between age and insurance charges among smokers
4. Comparing average insurance charges across different regions
5. Identifying which factors appear most associated with higher insurance charges

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis

### 1. Exploring the Dataset

I first examined the dataset's size, columns, data types, summary statistics, and missing values.

### 2. Smoking Status and Insurance Charges

I compared the average insurance charges for smokers and non-smokers.

The analysis showed that smoking status is strongly associated with higher insurance charges.

### 3. Age and Insurance Charges

I created a scatter plot to investigate the relationship between age and insurance charges among smokers.

The plot showed that insurance charges generally tend to increase with age among smokers.

### 4. Region and Insurance Charges

I used `groupby()` and `mean()` to calculate the average insurance charge for each region.

This allowed me to identify which region had the highest average insurance charge.

### 5. Overall Findings

Based on the analysis, smoking status appears to be the factor most strongly associated with high insurance charges. Age also appears to be associated with higher charges, particularly among smokers. Regional differences were smaller compared with the difference between smokers and non-smokers.

These findings describe associations in the dataset and do not establish causation.

## Dataset

The dataset was obtained from Kaggle:

https://www.kaggle.com/datasets/mragpavank/insurance1

The raw dataset is not included in this repository because its redistribution license is unspecified.

## Project Structure

```text
insurance-charges-analysis/
│
├── insurance_analysis.ipynb
└── README.md
```

## Future Improvements

Possible improvements to this analysis include:

- Exploring additional relationships between variables
- Creating more detailed visualizations
- Performing statistical analysis
- Applying more advanced data analysis techniques
