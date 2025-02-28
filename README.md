This project uses Logistic Regression and Random Forest Classification to predict 
features that affect employee turnover. The target variable, Attrition, was treated with Label 
encoder to fit both models. For the categorical data, the pandas get_dummies function was used 
to transform the variables into numerical values that can be applied in our algorithm. The dataset 
was split into an 80/20 train-test split and was treated with a scaler to normalize the values so 
that metrics that have a high value do not affect the performance of the models. Finally, even 
though only 2 models were used, the Random Forest classification was repurposed with 
hyperparameter tuning to see if finding the right parameters would improve the performance of 
the model.
