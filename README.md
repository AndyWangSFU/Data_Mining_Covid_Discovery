# CMPT 459 Fall 2020: Data Mining
# Project: Data Mining Approach to Analyze Covid-19 Dataset
**Oct - Dec 2020**

**Team** - Haiyaa

**Members** - Andy Wang, Qirui Wu, Liyang Zhou

# Problem Statement

The outbreak of Coronavirus disease 2019 (Covid-19) started with first cases in December 2019 in Wuhan, China. The high prevalence of Covid-19 has made it a new pandemic across almost all the countries with positive cases. Hence, how to correctly and effectively predict the outcome of Covid- 19 throughout the world is not only imperative for researchers to gain a more comprehensive understanding of the disease, but also crucial for the public to realize its potential impact of our life.

In this data mining project, we aim to select some most popular machine learning models, tune different hyperparameters, and use the best tuned models to predict the outcome (hospitalized, non- hospitalized, recovered or deceased) of a case, based on statistics from two publicly available Covid-19 datasets. We will also do a robust evaluation on their performance, specially focusing on correct predictions on the “deceased” cases because they are the most essential.

# Dataset Description
The original Covid-19 dataset contains two separate files. All information was extracted and frozen on September 20, 2020. Here is a general overview of each of them. More information is available from their GitHub main pages.
• Case Dataset: this contains some personal data (e.g., age) and outcomes for individual cases. (https://github.com/beoutbreakprepared/nCoV2019)
• Location Dataset: this contains the number of cases and health statistics based on locations. (https://github.com/CSSEGISandData/COVID-19)

# Exploratory Data Analysis
File “ExploratoryDataAnalysis.pdf” exhibits all tables and plots in order. Initially, we constructed a table to record the **Data Type, Number of Missing Values and Number of Unique Values**, for all attributes in two spreadsheets “cases.csv” and “location.csv”. We used different visualization ways to show attribute distribution based on its information and data types. 


# File Descriptions
The experimental results from best tuned models are stored in **459_Final_Report.pdf**. It also covers all tasks that are in the 3 milestones. The results for the other tuning models are stored in **/results/tuning.txt**. 

# Model Simulation
The easiest way to run the 4 Python models (Decision Trees, Random Forests, XGBoost and LightGBM) is to run **milestone3.ipynb** in Jupyter Notebook, where you can see a straightforward layout of each section. There are also some simulation results in the notebook.

There is a **KNN_README.pdf** which records all the CV tuning steps for the R model (KNN). To run the model, we recommend running **KNN.Rmd** in RStudio. **/plots/KNN_tuning.png** records all CV error rates for all tuning parameters.

