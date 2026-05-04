# Pancreatic Cancer (PDAC) Clinical Data Analysis
# Overview

This project explores clinical data from the TCGA pancreatic adenocarcinoma (PDAC) cohort, focusing on overall survival outcomes and key clinical variables.
The analysis demonstrates how Python can be applied to real-world clinical datasets to extract meaningful insights in oncology.

# Dataset

Data were obtained from The Cancer Genome Atlas (TCGA) pancreatic adenocarcinoma (PAAD) study via cBioPortal.

The dataset includes:
Patient demographics (age, sex)
Tumor staging (Pathologic Stage)
Overall survival data (status and time in months)

# Objectives
Perform data cleaning and preprocessing on clinical data
Analyze overall survival distribution
Explore relationships between survival and clinical variables
Evaluate survival differences across tumor stages

# Data Cleaning
Non-data metadata rows in the TCGA clinical file were excluded during data loading using the skiprows parameter
Missing values were handled by removing entries with incomplete clinical information using dropna()
Relevant clinical variables were selected for downstream analysis

# Methods
Data preprocessing with Pandas
Exploratory Data Analysis (EDA)
Data visualization using histograms, scatter plots, and boxplots

# Key Analyses
Overall survival distribution
Age vs overall survival relationship
Survival stratified by tumor stage
Multivariable visualization of survival patterns (age and stage)

# Results
Survival shows high variability across patients, reflecting disease heterogeneity
No strong linear relationship was observed between age and overall survival
A trend toward reduced survival in advanced tumor stages was observed, consistent with clinical expectations

# Tools
Python
Pandas
NumPy
Matplotlib

# Project Structure
PDAC_project_gp.ipynb – main analysis notebook

# Author

Pharmaceutical Chemist (PhD) transitioning into data-driven biomedical research and clinical data analysis.
