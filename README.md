# Default-Risk-Prediction---Lending-Club-Loans
## Overview
Default Risk due to asymmetric information has always been a top concern among Peer-to-Peer (P2P) investors. In this project, we apply predictive modelling techniques to predict default risk of borrowers on Lending Club platform. The model could be potentially integrated into portfolio optimization algorithms to maximize return given different risk preferences.
- Developed predictive models with 90.6% Recall rate to predict default risk using Logistic Regression, SVM and Random Forest Classification Trees with Grid-search hyperparameter tuning and 10-Fold cross validation. 
- Extended external data from U.S. Census Bureau to engineer new features and ranked the importance of features using Random Forest feature importance measure. Investigated trade-off between Precision (opportunity cost of not investing in healthy loans) and Recall (potential investment loss) through model comparisons of contour plots, quantified features’ predictive power and impact on risk classification rates using scatter/boxplots, Two-sample t-test and percentage change in odds of Logistic Regression.

Please access Project Report in the repository.

## Tools
Python: Pandas, Scikit-learn, Matplotlib, Seaborn.

## Dataset
Lending Club Statistics, 2018. Available: https://www.lendingclub.com/info/download-data.action [Accessed: 4 Aug, 2018].
