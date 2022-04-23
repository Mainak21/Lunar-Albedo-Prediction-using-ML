# Lunar-Albedo-Prediction-using-ML
Predicted lunar albedo with different material abundance maps Fe, Th, Ti using different Machine Learning models.

Found **Gradient Boosting Regressor** has less MSE loss.

**MSE Loss** of different ML models :
- Random Forest Regressor : 0.00116
- AdaBoost Regressor : 0.00108
- XGBoost Regressor : 0.00111
- K-Nearest Neighbor (KNN) Regressor : 0.00149
- Lasso Regressor : 0.002
- Gradient Boosting Regressor : 0.000956
- Multi Layer Perceptron (MLP) Regressor : 0.00135
- Decision Tree Regressor : 0.00166
- Ridge Regressor : 0.00102

![mse](https://github.com/Mainak21/Lunar-Albedo-Prediction-using-ML/blob/master/Results/mse.png)
![pred](https://github.com/Mainak21/Lunar-Albedo-Prediction-using-ML/blob/master/Results/prediction.png)
![trur](https://github.com/Mainak21/Lunar-Albedo-Prediction-using-ML/blob/master/Results/truevspredicted.png)
