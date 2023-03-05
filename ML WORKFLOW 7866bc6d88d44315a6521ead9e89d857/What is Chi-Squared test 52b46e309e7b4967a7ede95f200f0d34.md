# What is Chi-Squared test

The chi-squared test is a statistical test that is used to determine the association between two categorical variables. It measures the difference between the observed frequencies of the variables and the frequencies that would be expected if there was no association between them. It is commonly used in feature selection for categorical data, where it can be used to evaluate the relationship between a feature and the target variable.

The chi-squared test statistic is calculated by summing the squared differences between the observed and expected frequencies for each category, divided by the expected frequency. The test statistic is then compared to a chi-squared distribution with a certain number of degrees of freedom, which is determined by the sample size and the number of categories.

A small p-value (typically less than 0.05) indicates that there is a significant association between the two variables, while a large p-value suggests that there is no association. The chi-squared test can be used to select features for a model by selecting the features with the smallest p-values.

It's important to mention that Chi-squared test assumes that the variables are independent and that the sample size is large enough. It's not recommended to use it with small sample size.