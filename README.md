# dsa5202-advanced-ml-topics
multiclass classification; data with unknown origin

This was a project (individual) for class dsa5202 (June-2023), with a kaggle-like component. A dataset was provided, with input dimension 400 and output dimension 9. The task consisted of building a model that learns how to classify this dataset. For fairness, the dataset was anonymized. 

The data set we had access to consists of:

I. ([x_train](https://drive.google.com/file/d/1HaaYSqXT6USPY4T9eVd0fbRbXa9P6QF8/view?usp=sharing), [y_train](https://drive.google.com/file/d/1HeWaHQUjyNj3Bec_2LLLSMAINHqvx4ca/view?usp=sharing)): to train model

II. ([x_test](https://drive.google.com/file/d/1HcZreZ4ppyykYfv9nYf4v8TrxsJdc7zs/view?usp=sharing), [y_test](https://drive.google.com/file/d/1Hjuq0FQaQlpBibcqpOVilHCU2w5c8E8E/view?usp=sharing)): to evalute model

III. ([x_new](https://drive.google.com/open?id=1HfZDV7xmniWZzmVFApjx4pRLHGZGZyT6&usp=drive_fs), ?): for x_new, the labels y_new *were not* provided. After the model was trained and finalised, we used it to predict the outputs for x_new and submitted the prediction results. Our models were ranked by comparing our prediction file with the true labels for x_new (which only the professor has access to). There were two leaderboard updates prior to the final submission.

I was ranked 9th and 2nd for the 1st and 2nd leaderboard respectively.

| trial                         | test acc (model)                        | leaderboard acc (dev. from test acc) | leaderboard rank |
|:------------------------------|:----------------------------------------|:-------------------------------------|:-----------------|
| 1 (5-June)                    | 0.8707 (LightGBM)                       | 0.864667 (-0.006)                    | 9                |
| 2 (12-June)                   | 0.9044 (SVC, "tuned")                   | 0.892888 (-0.1212)                   | 2                |
| 3 (17-June, final submission) | 0.9056 (SVC, "tuned", reduced features) | NA                                   | NA               |

