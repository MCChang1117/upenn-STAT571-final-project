# Housing Rental Pricing Prediction

### Abstract

This repository is the final project of the course STAT 571 at the University of Pennsylvania (Spring 2022).

### Group Member (Responsibility)

* Pragyat Agrawal: Background, Plot
* Ruxuan Ji: Linear, LASSO, and Logistic Regression
* Meng-Chuan Chang: Random Forest, US Map Plot, Data Wrangling, Model Summary

### Data

#### No Data File

Since the size of data used in this homework is too big (> 100 MB) that Github rejects us to upload those files, I make a setting that Git would not track those data files (.csv format). 

Therefore, if you want to run this homework, make sure you download the data from the following links and put them inside `/data` folder.

* `/data/Rental_Properties.csv`
* `/data/income.csv`
* `/data/Rental_Properties_20000.csv` (filtered dataset)

#### Data Source

* [`/data/Rental_Properties.csv`](https://www.kaggle.com/datasets/elizabethveillon/us-rental-listings-summer-2021)
* [`/data/income.csv`](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2019-zip-code-data-soi)

### Output File

* `final-project.Rmd`
* `final-project.pdf`

### Model File

In this project, we store several `.RData` after training random forest model to save further running time

* `/data/rf_tune_1_150.RData` - `/data/rf_tune_10_150.RData`
* `/data/rf_model_3_500.RData`
* `/data/rf_model_4_100.RData`