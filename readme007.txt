No. 007

Preprocession method: 
	step1.Drop variables that have a very low variation (In R)（from 006)
	step2.Drop variables that have a high collinearity(>0.75)(In R)（from 006)
	step3.Backward stepwise selection(stepAIC from the MASS package)(In R)（from 006)
	step4. Drop variables that have a very low correlation with the target				(In Python)（from 006)
	step5. Lasso （from 006)
	step6. add 6 features (SelectKBest(mutual_info_regression, k=6))(In Python)
	


Outliers Detection (In Python): 

	method: DBSCAN Clustering (Density_based spatial clustering of 		application)

	Visualisation: PCA

Model training (In Python)

	Dummy (as the baseline)
	Decision Tree
	Random Forest
	Linear Regression
	Ridge Regression
	Lasso regression
	ElasticNet
	Partial Least Squares
	Polynomial Regression
	Neural Networks
	K-Nearest Neighbors


  