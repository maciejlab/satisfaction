# Satisfaction

Exploring the reasons for life satisfaction of GB citizens using logistic regression.

### Data

The data comes from the European Social Survey, runda 10: https://ess-search.nsd.no/
European Social Survey data is licensed under CC BY-NC-SA 4.0.

### Why?

The project was prepared to explore the main determinants of how UK citizens feel about life satisfaction. A model was prepared to predict whether a person with specific characteristics would rate their satisfaction as high or low.

### Conclusions

The final logistic regression model on the test data reached an AUC of 0.72, which is a satisfactory result. In the process of eliminating statistically insignificant variables, 4 explanatory variables were included in the final model: age, health, social and income. The model correctly identified 82% of cases where the theoretical values matched the actual ones.

Interpretation of the odds ratio shows that the health status of people in each successive category reduces the chances of life satisfaction by about 41.3%. In addition, belonging to next categories of income or intensity of social interaction increase the chances of life satisfaction by about 42-46%.

### Techniques

The project was written using the Python language and libraries: pandas, numpy, matplotlib, seaborn, statsmodels, sklearn.

### What else could be done?

It is possible to try to improve the model by adding new variables that may have been omitted from the initial analysis and also have a strong impact on life satisfaction. In addition, the model could test interactions between variables or transformations of continuous variables.