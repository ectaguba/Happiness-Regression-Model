### Feature Correlation w/ Label (Happiness)
![correlations](https://github.com/user-attachments/assets/094b7cc4-992b-4580-b710-59682371276e)

### Model Performance Metrics in Stepwise Feature Selection
Starting with the top correlated features, I added the next highly correlated feature and evaluated the new model's performance.

![metrics](https://github.com/user-attachments/assets/1f11cdea-0190-43fb-91ca-126a8c6c1f63)

### Model Performance
I tested standalone and ensemble models and found that a stacked model of GBDT, linear regression, and KNN gave the best scores (RMSE = 0.126, R2= 0.983, Time: 16s)

![models](https://github.com/user-attachments/assets/62a3df5d-ba2a-4fd8-a7e3-20dc74e63547)
