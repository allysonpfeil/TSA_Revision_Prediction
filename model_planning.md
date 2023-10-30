Goal: revision predictions after primary surgery

Features: TBD

Model: TBD based on the database, features, number of cases, etc. Some thoughts...

I want this project to be accessible to interested medical staff that may not have sophisticated algorithm knowledge, so I think it might be most beneficial to provide resources that can determine the model for the medical personnel. And given that I don't know yet what the data looks like, maybe accounting for multiple models will be worthwhile.

Models that preliminarily would/should be considered:  
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machines
  - Neural Network
  - Gradient Boosting

So far, I have written a grid search that will rank the models based on accuracy. However, a comparison between accuracy results and AUC ROC will likely be needed. By considering both, we will be choosing the most effective model for the specific problem.
