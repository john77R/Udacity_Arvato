# Udacity_Arvato
Capstone project for Udacity's Data Science Nano Degree in conjunction with Bertelsmann Arvato Analytics

Overview

The aim of this project was to apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These identified segments can then be used for direct marketing campaigns towards audiences that will have the highest expected rate of returns.

Repository Contents

The repository contains the final Jupyter notebook with the analysis and a copy in html format.

Dependencies

pandas
numpy
matplotlib
seaborn
sklearn

### Summary of results:
Basic models such as random forest & SVC lacked the complexity to capture the data set to produce a reasonable accurate result. MLPC was very prone to over fitting using the Sklearn implementation backed with grid search SV, again this produced poor results. GradientBoostingClassifier showed promising results for 77% ROC on grid search.
GradientBoostingClassifier showed promising results for 77% ROC on grid search.Best CV score = 0.767:

1. Model	                ROC
2. Random Forest	        0.713
3. SVC	                  0.69
MLPC	                0.631
Gradient bosted	      0.755
Final Gradient bosted	0.77
