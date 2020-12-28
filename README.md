# CMPT 459 Fall 2020: Data Mining
# Project: Data Mining Approach to Analyze Covid-19 Dataset
# Oct - Dec 2020

**Team** - Haiyaa

**Members** - Andy Wang, Qirui Wu, Liyang Zhou

# Problem Statement

The outbreak of Coronavirus disease 2019 (Covid-19) started with first cases in December 2019 in Wuhan, China. The high prevalence of Covid-19 has made it a new pandemic across almost all the countries with positive cases. Hence, how to correctly and effectively predict the outcome of Covid- 19 throughout the world is not only imperative for researchers to gain a more comprehensive understanding of the disease, but also crucial for the public to realize its potential impact of our life.

In this data mining project, we aim to select some most popular machine learning models, tune different hyperparameters, and use the best tuned models to predict the outcome (hospitalized, non- hospitalized, recovered or deceased) of a case, based on statistics from two publicly available Covid-19 datasets. We will also do a robust evaluation on their performance, specially focusing on correct predictions on the “deceased” cases because they are the most essential.


**File Descriptions**
The experimental results from best tuned models are stored in **459_Final_Report.pdf**. It also covers all tasks that are in the 3 milestones. The results for the other tuning models are stored in **/results/tuning.txt**. 

The easiest way to run the 4 Python models (Decision Trees, Random Forests, XGBoost and LightGBM) is to run **milestone3.ipynb** in Jupyter Notebook, where you can see a straightforward layout of each section. There are also some simulation results in the notebook.

There is a **KNN_README.pdf** which records all the CV tuning steps for the R model (KNN). To run the model, we recommend running **KNN.Rmd** in RStudio. **/plots/KNN_tuning.png** records all CV error rates for all tuning parameters.

