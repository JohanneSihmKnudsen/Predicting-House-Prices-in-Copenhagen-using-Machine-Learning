This file contains instructions on how to run the code that are a part of the master thesis "Predicting House Prices in Copenhagen using Machine Learning".

Data from the the danish websites www.boligsiden.dk, www.dingeo.dk, www.hvorlangterder.dk and accessible from StatBank Denmark, Statistics Denmark are scraped in the notebook "Getting data.ipynb". The raw data collected are denoted "df_final.csv" and can be found in the folder "Endeligt data".

In order to clean the data and to run the statistical analysis, make preprocessing and perform predictive models the following notebooks should be executed in the stated order: 

"Statistics.ipynb" - deletes outliers, descriptive statistics and exploratory data analysis are performed.
"Prepossessing.ipynb" - correlations between variables are reviewd, some variables are deleted, embedding of categorical variables, transformation of variables
"Relative location and zipcode.ipynb" - 
"Random split.ipynb" - OLS model with random versus time dependent split are analyzed
"Model.ipynb" - All 6 models are fitted, results are presented along with diagnostics plots.