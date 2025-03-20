# house_price_prediction

## Data
[House Price](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)：With 79 features and total 2919 records describing (almost) every aspect of residential homes in Ames

## Model Selection
**Regression model with Lasso**

Reason：
- Have a set of features related to the target variable
- Sufficient training data
- Handle collinearity
- Improve the predictive performance and interpretability

## Results
![download](https://github.com/user-attachments/assets/aedb6242-e822-40eb-9c6c-f27d7f2492b2)
- Best parameter combination selected by the model: {'alpha': 0.001}

- Best score (Negative Mean Absolute Error): -0.091158641352624

- Performance evaluation on the training set:
  R-squared value: 0.9284
  RMSE: 0.1070
  MAPE: 0.0062

- Performance evaluation on the test set:
  R-squared value: 0.8935
  RMSE: 0.1311
  MAPE: 0.0071

## Report
[PPT (in English)](https://github.com/user-attachments/files/19358079/ManagementScience_final_ppt_G3.pdf)
[PDF (in Chinese)](https://github.com/user-attachments/files/19358090/group3_final_report.pdf)
