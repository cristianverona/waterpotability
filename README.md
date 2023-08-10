# Water Potability

This is my final project for the Neural Academy master course. I began with a publicly available dataset on Kaggle
and applied several techniques learned during the course to analyze it.

## Introduction

The project's objective was to classify water samples as either potable or non-potable based on specific chemical
and physical parameters. One would expect a clear distinction between the two categories for each feature,
considering legal limits should ensure a definite separation. Hence, theoretically, a simple tree classifier
should be capable of accurately characterizing our dataset.

## Data Analysis and Modeling

Contrary to expectations, upon reviewing feature distributions, it becomes evident that a distinct separation between
potable and non-potable waters is lacking. Various models were tested in an attempt to address the classification issue,
but the results differed significantly from expectations. 
Among the tested classifiers, the most effective model is the Random Forest Classifier
(Potable water F1-score = 0.55, Non-potable water F1-score = 0.69), while XGBoost produced similar performance.

### Conclusions

Unfortunately, the data's origin remains unknown, yet it's clear that something irregular is present. 
Nonetheless, I consider analyzing this dataset an excellent exercise in cultivating critical thinking,
an essential skill when confronting Data Science challenges.




