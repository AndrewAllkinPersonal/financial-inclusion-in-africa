# Financial Inclusion in Africa

## Description

Financial inclusion remains one of the main obstacles to economic and human development in Africa. For example, across Kenya, Rwanda, Tanzania, and Uganda only 9.1 million adults (or 14% of adults) have access to or use a commercial bank account.

Traditionally, access to bank accounts has been regarded as an indicator of financial inclusion. Despite the proliferation of mobile money in Africa, and the growth of innovative fintech solutions, banks still play a pivotal role in facilitating access to financial services. Access to bank accounts enable households to save and make payments while also helping businesses build up their credit-worthiness and improve their access to loans, insurance, and related services. Therefore, access to bank accounts is an essential contributor to long-term economic growth.

The objective of this competition is to create a machine learning model to predict which individuals are most likely to have or use a bank account. The models and solutions developed can provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania and Uganda, while providing insights into some of the key factors driving individuals’ financial security.

## Evaluation 
The evaluation metric for this challenge is Mean Absolute error, where 1 indicates that the individual does have a bank account and 0 indicates that they do not.

Your submission file should look like:

|     unique_id      | bank_account | 
|       :---:        |     :---:    |    
| uniqueid_1 x Kenya |       1      | 
| uniqueid_2 x Kenya |       0      | 
| uniqueid_3 x Kenya |       1      | 

## ML Algorithms to Consider
Since this is a binary classification problem (Yes or No), the following models can be used:    
1. Logistic Regression
2. Random Forest
3. Gradient Boosting
    - XGBoost
    - LightGBM
    - CatBoost
4. Support Vector Machines (SVM)
5. Naive Bayes
6. K-Nearest Neighbours (KNN)

## Git Flow Process
There are 3 main branches:
- main
- feature/andrew
- feature/sven

Individual work must be done on the feature branches. Once you are ready to merge the changes on your feature into main, follow these steps:   
1. Ensure you have committed and pushed all changes on your feature
2. git checkout main
3. git pull
4. git checkout feature/{name}
5. git checkout -b main-rel/{description}
6. Push branch to remote (Publish Branch option on Visual Studio)
7. On GitLab:
    - create new merge request
    - source branch: main-rel/{description}
    - target branch: main
    - select "Assign to me"
    - create merge request
    - if there are no conflicts, merge

