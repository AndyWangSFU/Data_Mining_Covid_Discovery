# CMPT 459 Data Mining
# Project Milestone 3

**Team** - Haiyaa

**Members** - Andy Wang, Qirui Wu, Liyang Zhou

**Goal**
The data mining project goal will be to predict the outcome of a case. It is also crucial to predict the ‘deceased’ label correctly, with few ‘False Negatives’, i.e. the ‘recall’ for class ‘deceased’ should be high. 

Milestone 3 is about tuning the hyperparameters, performing cross validation and comparing the models based on their performances. In total, we built and tuned 5 models (4 in Python; 1 in R) for this milestone.


**File Descriptions**
The experimental results from best tuned models are stored in **459_Final_Report.pdf**. It also covers all tasks that are in the 3 milestones. The results for the other tuning models are stored in **/results/tuning.txt**. 

The easiest way to run the 4 Python models (Decision Trees, Random Forests, XGBoost and LightGBM) is to run **milestone3.ipynb** in Jupyter Notebook, where you can see a straightforward layout of each section. There are also some simulation results in the notebook.

There is a **KNN_README.pdf** which records all the CV tuning steps for the R model (KNN). To run the model, we recommend running **KNN.Rmd** in RStudio. **/plots/KNN_tuning.png** records all CV error rates for all tuning parameters.

