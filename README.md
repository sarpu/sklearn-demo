# Scikit-Learn Demo

This repository is a template for machine learning projects in Scikit-Learn.

Your Tasks:
1. Create your own preprocessing piplines. 
  - Create a pipeline to use median imputation for numeric columns
  - Create a pipeline using the standard scaler to scale all numeric values
  - Create a pipeline that uses the "most frequent" strategy for categorical variables
  - Create a pipeline that one-hot encodes categorical variables
2. Establish the preprocesing pipeline by columns
3. With your new pipelines, now train a Random Forest model
4. Perform Cross Validation and modify the n_estimators and and max_depth parameters
5. Examine the difference in the way feature importances are extracted in a Random Forest model. This will likely be different for each type of model
6. Take a look at this article to understand how to develop your own custom piplines to transform your data: https://towardsdatascience.com/creating-custom-transformers-for-sklearn-pipelines-d3d51852ecc1
