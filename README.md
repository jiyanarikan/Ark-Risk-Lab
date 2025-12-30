# quant-risk-lab

Supply chain risk modelling using linear algebra and machine learning.

This project uses econometric theory (matrices/OLS) and data science (prediction). 
It takes raw procurement data, reduces dimensionality using PCA, and flags high-risk contracts.


Key Features

- Manual PCA: Implementing Eigen-decomposition from scratch (using numpy) to fix multicollinearity.
- PCA Heat Maps: Observing potential outlier causes through compressed 2D/3D PC graphical analysis.
- Risk Modelling: Training a Gradient Boosted Tree (XGBoost) to detect failure patterns.
- Smote Analysis: Dealing with imbalances in failure to success tender classifications.
