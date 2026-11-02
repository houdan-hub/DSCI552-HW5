# DSCI552 Homework 5

Tianbo Hou

Executed notebook for DSCI 552 Homework 5:

1. **Decision Trees as Interpretable Models** - Acute Inflammations data set (120 patients, 2 labels): loading (UTF-16, TAB-separated, comma decimals), multi-output decision tree + plot, IF-THEN rule extraction (KDnuggets method), and cost-complexity pruning to minimal interpretable trees (joint tree and one tree per label).

2. **The LASSO and Boosting for Regression** - Communities and Crime data (1495 train / 499 test): non-predictive columns dropped, train-set mean imputation, correlation matrix, coefficient of variation, top floor(sqrt(128)) = 11 CV features with scatter/box plots, then OLS, Ridge, LASSO (raw and standardized), PCR, and XGBoost with L1 regularization (`reg_alpha`), all tuned by 5-fold cross-validation and compared by test MSE.

Data files are in `data/` and are loaded with relative paths, so the notebook runs as-is.
