# Choose proper tutors for math exam

## Algorithms of data analysis. Classification. 

https://www.kaggle.com/c/gb-choose-tutors

In this internal GeekBrains competition we had to make **classification** model and weren't allowed to use external libraries.

I made the custom **logistic regression** function. I **won top-3** place with a score of **AUC ROC = 0.98392** on test data:

<img src="img/3-rd place.png"  width="800">


### Usage

It have some next steps into main project file [Classification.Choose tutors.ipynb](https://github.com/hildar/choose-tutors/blob/main/Classification.%20Choose%20tutors.ipynb):

Make functions for calculate standard scale, sigmoid and log loss function:

<img src="img/logloss.png"  width="500">

Make evaluate and metric functions:

<img src="img/evaluate.png"  width="300">
<img src="img/roc.png"  width="300">

Then fit and evaluate result:

<img src="img/roc curve.png"  width="300">

At the end it is need to predict on test data, save *submission.csv* and send to Kaggle.
