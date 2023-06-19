# dsa5202-advanced-ml-topics
multiclass classification; data with unknown origin

This was a project (individual) for class dsa5202 (June-2023), with a kaggle-like component. A dataset was provided, with input dimension 400 and output dimension 9. The task consisted of building a model that learns how to classify this dataset. For fairness, the dataset was anonymized. The data set we had access to consists of:

I. (x_train, y_train): you can use this to train your model

II. (x_test, y_test): you can use to evalute your model

III. (x_new, ?): for x_new, the labels y_new *were not* provided. After the model was trained and finalised, we used it to predict the outputs for x_new and submitted the prediction results. Our models were ranked by comparing your prediction file with the true labels for x_new (which only the professor has access to). There were two leaderboards update prior to the final submission.

I was ranked 9th and 2nd for the 1st and second leaderboard respectively.

| Trial.          | Test Acc (model)       | Leaderboard acc (dev. from test acc)| | Leaderboard rank|
|:----------------|:-----------------------|:--------------------|:--------------------|
| 1 (5-June)      | 0.8707 (LightGBM)      | 0.864667 (-0.006)   | 9   |
| 2 (12-June)     | 0.9044 (SVC, "tuned")  | 0.892888 (-0.1212)  | 2   |
| 3 (17-June, final subimssion)     | 0.9056 (SVC, "tuned", reduced features)  | ?  | ?   |
