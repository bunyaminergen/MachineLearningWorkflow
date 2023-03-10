# What is Leakage

Leakage is a phenomenon that occurs in the machine learning process when information from the test set is used to create or train a model, which leads to artificially inflated performance on the test set. This can happen when the model is overfitting to the training data, or when features in the test set are inadvertently included in the training data.

Leakage can occur in various forms and can have different sources, such as :

- Data leakage: when sensitive data from the test set is used to train the model.
- Time leakage: when the model is trained using information from the future that is not available at the time of prediction.
- Target leakage: when the model is trained using information from the target variable.
- Feature leakage: when the model is trained using information from features that should not be used.

Leakage is a problem in machine learning because it can lead to artificially high accuracy scores, which can be misleading in real-world applications. Therefore, it is important to detect and prevent leakage in the machine learning process to ensure the model's generalization performance.

[https://en.wikipedia.org/wiki/Leakage_(machine_learning)](https://en.wikipedia.org/wiki/Leakage_(machine_learning))