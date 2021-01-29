# Contents
1. nb directory contains notebooks , cache file and json files to summarize models performance.
2. *Churn-Prediction-v1.0.ipynb*: a quick and dirty prorotype with the main objective of understanding the data and experimenting different feature 
engineering and modeling approaches
3. *Churn-Prediction-v1.1.ipynb*: a cleaner version with feature generation function well written with simple unit tests

# Running and Results
1. create a separate venv (python 3.7) 
2. pip3 install -r requierments.txt # to install requirements
3. run the v1.1 notebook
4. Accuracy results are dumped into json files
   nb/lr_perfromance.json : for logisitic regression
   nb/adaboost_performance.json : for adaboost
   nb/nn_performance.json: for neural networks
5. The structure of the json is that it show what is the best score and model based on grid search / cross validation for the 3 scores : roc_auc, precsion and recall
6. The total code runnign time (when experiment the 3 model classes : logistic regression, adaboost and Neural Networks)
    =  ?? mins 