# Udacity_Arvato
Capstone project for Udacity's Data Science Nano Degree in conjunction with Bertelsmann Arvato Analytics

Overview

The aim of this project was to apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These identified segments can then be used for direct marketing campaigns towards audiences that will have the highest expected rate of returns.

Repository Contents

The repository contains the final Jupyter notebook with the analysis

Dependencies

. pandas
. numpy
. matplotlib
. seaborn
. sklearn

### Summary of results:
Basic models such as random forest & SVC lacked the complexity to capture the data set to produce a reasonable accurate result. MLPC was very prone to over fitting using the Sklearn implementation backed with grid search SV, again this produced poor results. GradientBoostingClassifier showed promising results for 77% ROC on grid search.
GradientBoostingClassifier showed promising results for 77% ROC on grid search.Best CV score = 0.767:

1. Model	                ROC
2. Random Forest	        0.713
3. SVC	                  0.69
4. MLPC	                  0.631
5. Gradient bosted	      0.755
6. Final Gradient bosted	0.77

for more details see the following **blog post:** https://johnxringrose.medium.com/customer-segmentation-report-for-arvato-financial-solutions-2d4b0f59182c

### Acknowledgements

**Data set** thanks to Bertelsmann Arvato & Udacity for providing the dataset.

**Course material** thanks to Udacity for the excellent course. Found here:
https://www.udacity.com/course/data-scientist-nanodegree--nd025

**References** 
1. https://github.com/jamiepotter17/arvato/blob/main/Identify_Customer_Segments.ipynb

2. https://github.com/djirmgard/arvato-udacity-project/blob/master/Arvato%20Project%20Workbook.ipynb

3. https://github.com/mkeisenbach/arvato/blob/master/segmentation/Arvato%20Project%20Workbook.ipynb

4. https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-imbalanced-classification/
. ( see full list in python note book)

### Licence:
MIT Licence.
