# Quantitative structure-activity relationship (QSAR)

As a mother, you do everything possible to protect your baby during the early stages of pregnancy. Despite the protective role of the placenta, many molecules, including those from drugs and even the environment, are present in your bloodstream and manage to cross the placenta. QSAR aims to use machine learning to build models that predict the ability of chemical molecules to cross the placenta.

<img src="projet_QSAR.jpg" alt="isolated" width="500"/>

## Preprocession method: 

- step1.Drop variables that have a very low variation (In R)
- step2.Drop variables that have a high collinearity(>0.75)(In R)
- step3.Backward stepwise selection(stepAIC from the MASS package)(In R)
- step4. Drop variables that have a very low correlation with the target (In Python)
- step5. Lasso 
- step6. add 6 features (SelectKBest(mutual_info_regression, k=6))(In Python)
	


## Outliers Detection (In Python): 

- method: DBSCAN Clustering (Density_based spatial clustering of application)
- Visualisation: PCA

## Model training (In Python)

- Dummy (as the baseline)
- Decision Tree
- Random Forest
- Linear Regression
- Ridge Regression
- Lasso regression
- ElasticNet
- Partial Least Squares
- Polynomial Regression
- Neural Networks
- K-Nearest Neighbors
