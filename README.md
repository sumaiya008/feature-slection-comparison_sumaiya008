# dsei2100s23hw4p3-feature-selection
The objective of this notebook is to explore and compare various feature selection techniques on scikit-learn's diabetes dataset to identify the most significant features. This process helps in pinpointing the features that contribute the most to machine learning models, reducing dataset dimensionality, addressing potential overfitting concerns, and decreasing computation and memory requirements.

The feature selection methods investigated in this notebook include:

- Pearson correlation coefficient using **r_regression** from scikit-learn (univariate feature selection)
- Mutual information using **mutual_info_regression** from scikit-learn (univariate feature selection)
- Random forest feature importance using **RandomForestRegressor** from scikit-learn (multivariate feature selection)
- Recursive feature elimination using **RFE** from **sklearn.feature_selection** with a Support Vector Regressor (SVR) (multivariate feature selection)
