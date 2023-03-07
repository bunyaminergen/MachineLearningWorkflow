# Missing data

Missing data, also known as missing values, refers to observations in a dataset where one or more values are missing. This can occur for a variety of reasons, such as measurement errors, missing data collection, or respondents not providing an answer to certain questions.

Handling missing data is an important step in the data preparation process for machine learning, as it can have a significant impact on the performance of the model. There are several techniques for dealing with missing data, including:

1. Deletion: remove the observations or features with missing values from the dataset.
2. Imputation: fill in the missing values with estimates based on the existing data. Techniques include mean imputation, median imputation, mode imputation and multiple imputation.
3. Model-based imputation: impute the missing values by using a predictive model to estimate the missing data based on the other variables in the dataset.
4. Data augmentation: create new observations based on the existing data to supplement the missing data.

Which technique to use depends on the specific use case and the amount of missing data present in the dataset. For instance, if the missing data is random and the amount of missing data is small, deletion or imputation may be appropriate. On the other hand, if the missing data is not random and the amount of missing data is large, model-based imputation or data augmentation may be more appropriate.