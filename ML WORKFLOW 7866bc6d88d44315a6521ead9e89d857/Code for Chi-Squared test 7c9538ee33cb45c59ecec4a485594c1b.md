# Code for Chi-Squared test

Here is an example of how to use the chi-squared test to select features in Python using the **`chi2`**
 function from the **`sklearn.feature_selection`**
 module:

```python
from sklearn.feature_selection import SelectKBest
from sklearn.feature_selection import chi2

# Create an instance of SelectKBest with the chi-squared test
selector = SelectKBest(score_func=chi2, k=10)

# Fit the selector to the data and get the selected features
X_new = selector.fit_transform(X, y)

# Get the indices of the selected features
selected_features = selector.get_support(indices=True)

# Print the selected feature indices
print(selected_features)
```

In this example, the **`SelectKBest`** class is used to select the top 10 features using the chi-squared test. The **`fit_transform`** method is used to fit the selector to the data and to transform the data to a new dataset containing only the selected features. The **`get_support`** method is used to get the indices of the selected features, which can then be used to access the selected features in the original dataset.

It's important to note that the **`X`** is the feature matrix and **`y`** is the target variable. **`k`** parameter defines the number of features you want to select.

You can also use the **`pandas.crosstab`** method to calculate the contingency table and use the **`scipy.stats.chi2_contingency`** to calculate the chi-squared test statistic and p-value.