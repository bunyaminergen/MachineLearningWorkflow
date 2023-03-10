# Model Validation

Model validation is a method used to measure the performance of a model. It is used to assess how well a model trained on training data will perform on unseen data (test data). Model validation is typically done by using a separate dataset, which is split into training and test sets. The model is trained on the training set and then evaluated on the test set. Model validation is important in preventing overfitting and underfitting problems. It is also used to select the best model among several models that were trained with different parameters or architectures, by comparing their performance on the validation dataset.

There are several methods for model validation, some of the common ones are:

1. Holdout method: This method involves splitting the dataset into two parts, a training set and a test set. The model is trained on the training set and then evaluated on the test set.
2. K-fold cross-validation: This method involves dividing the dataset into k subsets (folds) and training the model k times, each time using a different fold as the test set and the remaining k-1 folds as the training set. The performance of the model is then averaged across all k runs.
3. Leave-one-out cross-validation: This method is similar to k-fold cross-validation, but the value of k is set to the number of samples in the dataset, resulting in each sample being used as a test set once.
4. Bootstrap Aggregating (bagging) and Boostrap Averaging (bagging) : This method is used to improve the model's robustness. It creates several samples with replacement from the training set and then train a model for each sample. Finally, the predictions of each model are combined to make the final prediction.
5. Monte Carlo cross-validation: This method randomly splits the data into training and test sets multiple times, and then train the model and evaluate its performance each time. The final performance is the average performance across all the runs.
6. Pre-processing cross-validation : this method cross-validates not only the model but also the pre-processing steps.
7. Nested cross-validation: This method involves performing both model selection and model evaluation using cross-validation. The outer loop is used to select the best model among several candidates, while the inner loop is used to evaluate the performance of the selected model.
8. Time series cross-validation: This method is used when the data is collected over time, such as stock prices or weather data. It involves using a sliding window to split the data into training and test sets, and then training the model on the training set and evaluating it on the test set.
9. Stratified sampling: This method is used when the dataset is imbalanced, meaning that it contains different number of samples from each class. It involves randomly splitting the data into training and test sets, but making sure that the proportion of samples from each class is the same in both sets.

These are just a few examples of the model validation methods, and there are many more methods that have been developed to address specific types of problems or data. The choice of method depends on the specific problem, the dataset, and the research goals. It is always important to consider the dataset, the problem at hand and the resources available before selecting a validation method.

Note: Test setine asla dokunulmamali en son butun islemler bitince model hic dokunulmamis test verisi ile test edilmeli. Bu yuzden train, validation ve test olarak ayirmaliyiz veriyi.