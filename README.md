# Feature-selection-methods
Feature Selection is the process where you automatically or manually select those features which contribute most to your prediction variable or output in which you are interested in. Having irrelevant features in your data can decrease the accuracy of the models and make your model learn based on irrelevant features.

Filter Method: Filter feature selection methods use statistical techniques to evaluate the relationship between each input variable and the target variable, and these scores are used as the basis to choose (filter) those input variables that will be used in the model.

In wrapper methods, the feature selection process is based on a specific machine learning algorithm that we are trying to fit on a given dataset. ... Finally, it selects the combination of features that gives the optimal results for the specified machine learning algorithm.

Embedded methods combine the qualities' of filter and wrapper methods. It's implemented by algorithms that have their own built-in feature selection methods. Some of the most popular examples of these methods are LASSO and RIDGE regression which have inbuilt penalization functions to reduce overfitting.

Filter methods (ANOVA, Pearson correlation, variance thresholding)
Wrapper methods (forward, backward, and stepwise selection)
Embedded methods (Lasso, Ridge, Decision Tree)
