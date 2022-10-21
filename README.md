# Predict the amount of gold recovered from gold ore
This is the first integrated project of the Practicum DS course, combining Introduction to Machine Learning, Supervised Learning and Machine Learning in Business sprints.

## Description
Here we have a dataset on the process of extraction and purification of gold ore. We aim to build a model for predicting the amount of recovered gold. It would help to optimize production and eliminate unprofitable parameters.

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Next, we need to scale and encode the data. Afterward, we could proceed to model development.

## Conclusion
After preprocessing, we explored several models and picked the one that showed the best sMAPE score. The **Lasso Regressor** model has a score of 7.29. Also, we checked it against the dummy model, and the regressor showed a better result.