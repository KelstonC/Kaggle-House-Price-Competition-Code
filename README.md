# Kaggle-House-Price-Competition-Code
The first file, will contain the a XGBoost model, with EDA and hyperparameter tuning. This notebook resulted in a top 10% (at the time) in Kaggle's
house price competition.

My best score (RMSE:  0.12315) so far for the Kaggle House price Competition (around top 10%).

The second file, will contain not only a XGBoost model but also a LightGBM, SVR (support vector regression), KNN regression, Lasso regression, and a Elastic Net model.
This file contains many parts that are the same to the first, namely the EDA, but includes the other 5 models and an stacking model attempt - although the stacking model does not end up performing any better than the single XGBoost model. The worse result from the stacking model is likely do to overfitting.
