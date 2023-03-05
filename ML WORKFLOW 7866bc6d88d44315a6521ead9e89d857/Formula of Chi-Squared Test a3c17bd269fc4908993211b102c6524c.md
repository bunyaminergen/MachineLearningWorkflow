# Formula of Chi-Squared Test

The chi-squared test is a statistical test that is used to determine the association between two categorical variables. The formula for the chi-squared test statistic is as follows:

# $\chi^2 = \sum_{i=1}^{n} \frac{(O_i - E_i)^2}{E_i}$

where:

- $O_i$ is the observed frequency of the i-th category
- $E_i$ is the expected frequency of the i-th category, assuming that the two variables are independent.
- $n$ is the number of categories.

The expected frequency for each category is calculated by multiplying the marginal frequencies of the two variables, and dividing by the total sample size.

# $E_i = \frac{(r_i*c_i)}{N}$

Where $r_i$ is the row marginal, $c_i$ is the column marginal and $N$ is the total sample size.

The chi-squared test statistic is then compared to a chi-squared distribution with a certain number of degrees of freedom, which is determined by the sample size and the number of categories. The degrees of freedom for a two-way contingency table can be calculated as:

$df = (r - 1)(c - 1)$

Where $r$ is the number of rows, $c$ is the number of columns.

A small p-value (typically less than 0.05) indicates that there is a significant association between the two variables, while a large p-value suggests that there is no association.

In feature selection, the chi-squared test is used to evaluate the relationship between each feature and the target variable. It is commonly used for categorical data, and it can be used to select the features with the smallest p-values.

[https://www.youtube.com/embed/WXPBoFDqNVk](https://www.youtube.com/embed/WXPBoFDqNVk)

### Bonus:

**Latex** 

```latex
$\chi^2 = \sum_{i=1}^{n} \frac{(O_i - E_i)^2}{E_i}$

$E_i = \frac{(r_i*c_i)}{N}$

$df = (r - 1)(c - 1)$
```

### *Links to learn more:*

- [https://en.wikipedia.org/wiki/Chi-squared_test](https://en.wikipedia.org/wiki/Chi-squared_test)
- [https://mathworld.wolfram.com/Chi-SquaredTest.html](https://mathworld.wolfram.com/Chi-SquaredTest.html)
- [Corder, G. W.; Foreman, D. I. (2014), Nonparametric Statistics: A Step-by-Step Approach , New York: Wiley, ISBN 978-1118840313](https://www.researchgate.net/publication/274903105_Nonparametric_Statistics_A_Step-by-Step_Approach)