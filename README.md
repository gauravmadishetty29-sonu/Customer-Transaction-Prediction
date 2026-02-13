# Customer-Transaction-Prediction
The objective of this project is to built a model that predicts whether a customer will make a transaction in the future
--- Models Evaluated
1.>Logistic Regression  
2.>Random Forest  
3.>Gradient Boosting  
4.>XGBoost  

The dataset is imbalanced, ROC-AUC was used as the primary evaluation metric.

0 LogisticRegression	     0.864087
1	RandomForestClassifier	 0.787383
2	GradientBoostClassifier	 0.866831
3	XGBClassifier	           0.863007

Gradient Boosting achieved the highest ROC-AUC score and is selected as the final model.

