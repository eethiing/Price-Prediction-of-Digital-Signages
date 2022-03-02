# Price-Prediction-of-Digital-Signages

1. The scope of this experiment is quite small as the number of data was quite limited. 
2. Models : Random Fores and XgBoost
3. There might be other features that will contribute to the pricing index for digital signage.
4. This study presents the labeling of the features and the regression models that are viable for price prediction. 
5. Among the two regression models that were employed, Random Forest results proved to be superior with MAE of 0.0053, R2 of 0.9974, MSE of 0.00007 and OOB of 0.9973 but the time    taken to train Random Forest is longer which is around 1 minute 40 seconds whereas XGBoost is around 37 seconds. 
6. Besides, the feature importance that was computed by Random Forest is not skewed on only one feature whereas XGBoost feature importance computed that weather_main_label holds      almost 0.5 importance in the whole model. 
7. To reduce the time taken of the Random Forest model, the n_estimators were changed to 90 and the run time was 13 seconds only. 
8. This dataset was just limited to 2 weeks worth of data. 
9. Further experiments can be done using other features that are available with different regression models as well as studying each feature to understand the impact of it on the    price of digital signages. 
