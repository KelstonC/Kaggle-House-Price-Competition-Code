# Kaggle-House-Price-Competition-Code
The `first file` (*KHPC_FeatEng_jun13.ipynb*), will contain a `XGBoost model`, with exploratory data analysis (EDA) and hyperparameter tuning. This notebook resulted in a top 10% (at the time) in `Kaggle's` house price competition.

> My best score (RMSE:  0.12315) so far for the Kaggle House price Competition (top 10%).

The `second file` (*KHPC_Stacking_aug8.ipynb*), will contain not only a `XGBoost model` but also a `LightGBM`, `SVR (support vector regression)`, `KNN regression`, `Lasso regression`, and a `Elastic Net model`.
This file contains many parts that are the same to the first, namely the EDA, with the addition the other 5 models and a stacking model attempt - although the stacking model does not end up performing any better than the single XGBoost model. 

The worse result from the stacking model is likely do to overfitting.
