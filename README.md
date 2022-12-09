# Credit-risk-Scoring

When we receive a loan application, we need to make sure that if we give the money, the customer will be able to pay it back. Every application carries a risk of *default* — the failure to return the money. We’d like to minimize this risk: before agreeing to give a loan, we want to score the customer and assess the chances of default. If it’s too high, we reject the application. This process is called “credit risk scoring.”

The plan for the project is the following:
1. First, we get the data and do some initial preprocessing.
2. Next, we train a decision tree model from Scikit-learn for predicting the probability of default.
3. After that, we explain how decision trees work and which parameters the model has and show how to adjust these parameters to get the best performance.
4. Then we combine multiple decision trees into one model — a random forest. We look at its parameters and tune them to achieve the best predictive performance.
5. Finally, we explore a different way of combining decision trees — gradient boosting. We use XGBoost, a highly efficient library that implements gradient boosting. We’ll train a model and tune its parameters.

Credit risk scoring is a binary classification problem: the target is positive (“1”) if the customer defaults and negative (“0”) otherwise. For evaluating our solution, we’ll use AUC (area under the ROC curve), AUC describes how well our model can separate the cases into positive and negative ones. 

A walkthrough notebook for the project can be found [here](https://github.com/rohanj98/Credit-risk-default-prediction/blob/main/credit-risk-scoring.ipynb)
