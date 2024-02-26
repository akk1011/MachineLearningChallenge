# Data Challenge: Breaking classifiers

The goal of this challenge is to build datasets that are hard for Logistic Regression, but Decision Tree and vice versa.  

We will assess performance via F1-score using a 5-fold classifier. We should strive to achieve a difference of at least .02 in average F1-score. 

## Rules

1. We cannot use feature manipulation to cause a classifier to fail - e.g., decision trees are robust to ordinal-encoded data and insensitive to scaling; KNNs are highly sensitive to both.  We must encode our data in a manner that gives both algorithms the best chance they have to do well.
2. For a given dataset, any imputation / pre-processing must be identical across your algorithms.
3. We must use default parameter settings - i.e. no hyperparameter tuning to "force" a result.  However, we can tweak your data however we want!




