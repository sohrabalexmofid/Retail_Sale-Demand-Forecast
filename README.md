#  Retail_Sale-Demand-Forecast
Predict Walmart sales at store-day level for two year time-span.

![download](https://github.com/sohrabalexmofid/Retail_Sale-Demand-Forcast/assets/123208599/bb26f86f-9895-486c-a35b-cf075ecdec92)




Problem statement:

Demand Forecast is one of the key tasks in Supply Chain and Retail Domain in general. It is key in effective operation and optimization of retail supply chain. 
prediction of sales for each Store-Day level for one month is required. all the features are provided, actual sales that happened during that month and model evaluation needs to be provided accordingly. 

***
***Linear Regression***

EDA to see impact of variables over sales.

Dimensional Reduction techniques, PCA.

Single model for all stores, using storeid as a feature.

Separate model for each store.

Ensemble method, using Random forest or othe tree-based regressors.

Regularized regression to see if the performance is better for an unseen test set.


***Time-Series Model***

Time-series model on data taking time as the only feature, store-level training.

identifying yearly trends and seasonal months.

LSTM on the same set of features and comparison of result to traditional time-series model.

clustering stores using sales and customer as features. visualzing the results.



***Artificial Neural Network(ANN)***

ANN to predict store sales.

hyperoparameter tunining, experimenting with no of (layers, neurons, batch-size, epochs, learning-rate) and find best RMSE.

comparing model with tradional Ml based prediction models.
