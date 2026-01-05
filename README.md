### Bank Marketing Prediction



This project analyzes the Bank Marketing dataset to predict whether a client will subscribe to a term deposit.



#### Project Structure



notebooks/ → Jupyter notebooks with code and analysis



data/ → Dataset (CSV)



plots/ → Visualizations (confusion matrices, feature importance, model comparison)



models/ → Saved models (optional, retrainable from notebook)



requirements.txt → List of dependencies to install with pip install -r requirements.txt



#### Models Tested



-Logistic Regression (baseline)



-Logistic Regression with class weights



-Random Forest



-XGBoost



#### Key Findings



-Class imbalance was a major challenge.



-Logistic Regression with class weights improved recall for “yes” clients.



-XGBoost achieved the highest recall (92%) with lowest false negatives.



Business Insight

High recall is more valuable in marketing — better to catch almost all potential subscribers, even if some false positives occur.

