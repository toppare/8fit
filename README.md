<img src="./8fit_Appicon_1024.png" width="200">

## Subscriber to Customer prediction


When users subscribe to 8fit app, they first do a trial. When they stay with the app after the trial, 
they pay and we call them customers. Notice that there are subscribers which do not turn into a customer, 
but every customer is also a subscriber. 

There are two files:

1) train_data.csv: user_id, channel, age, os, gender, country and customer. 
All users in this file have done a subscription. 
The column customer is 1 if the subscription converted to a customer and 0 if not.
2) test_data.csv: The same for other users without the customer column.

### The tasks:

- Do a small explorative analysis and give an overview of the data in train_data.csv.

[Explorative Analysis](./baran_toppare_analysis_predictions.ipynb)

- Predict the values of customer (0 or 1) for users in test_data.csv. 

[Predictions](./Baran_Toppare_predictions.csv)
