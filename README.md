# Bankruptcy-Prevention-Project
Tags: Data Mining, Machine Learning, Data Visualization.
Summary:
Bankruptcy prediction is the task of predicting bankruptcy and various measures of financial distress of firms, and is important due to the relevance for creditors and investors in evaluating the likelihood that a firm may go bankrupt.

The aim of predicting financial distress is to develop a predictive model that combines various econometric parameters which allow foreseeing the financial condition of a firm. In this project we document our observations as we explore, build, and compare, some of the widely used classification models:

Gaussian Naïve Bayes
Logistic Regression
Decision Trees
Random Forests
Extreme Gradient Boosting
Balanced Bagging
We have chosen the Polish companies’ bankruptcy data set where synthetic features were used to reflect higher-order statistics.

We begin by carrying out data preprocessing and exploratory analysis where we impute the missing data values using some of the popular data imputation techniques like Mean, k-Nearest Neighbors, Expectation-Maximization and Multivariate Imputation by Chained Equations (MICE).

To address the data imbalance issue, we apply Synthetic Minority Oversampling Technique (SMOTE) to oversample the minority class labels.

Later, we model the data using K-Fold Cross Validation on the said models, and the imputed and resampled datasets.

Finally, we analyze and evaluate the performance of the models on the validation datasets using several metrics such as accuracy, precision, recall, etc., and rank the models accordingly.
