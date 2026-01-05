### Bank Marketing Prediction



This project uses machine learning to predict whether a bank client will subscribe to a term deposit. It covers data preparation, feature encoding, model training, evaluation, and visualizations.



#### Project Structure



-"notebooks/" — full workflow



-"data/" — dataset files



**-"plots/" — charts and visualizations**



-"models/" — saved models



-"requirements.txt" — dependencies



#### Models Used



-Logistic Regression



-Logistic Regression (class weights)



-Random Forest



-XGBoost



#### Key Insights



**-Overall economic conditions were the strongest drivers of predictions.**

Indicators related to employment levels and economic stability contributed the highest share of model importance.



**-Client engagement also played a meaningful role.**

Longer conversations and positive outcomes from previous marketing efforts increased the likelihood of subscription.



**-The dataset is highly imbalanced.**

Only a small portion of clients subscribe, so models must prioritize recall to avoid missing potential subscribers.



**-XGBoost performed best** by capturing both economic context and client‑level behavior.



#### Business Insight



Banks want to improve the effectiveness of marketing campaigns by focusing on clients most likely to subscribe.

This model supports that goal by:



**-Highlighting when clients are more receptive**, especially during periods of stronger economic conditions



**-Prioritizing clients who show higher engagement**, helping call‑center teams focus their time where it matters



**-Reducing wasted calls** on low‑probability leads



\-**Improving ROI** through better targeting and smarter resource allocation



The insights help marketing teams understand not just who is likely to subscribe, but why, making campaign planning more strategic.



#### How to Run



pip install -r requirements.txt



Run:

notebooks/bank\_marketing.ipynb



#### Dataset Attribution



This project uses the Bank Marketing dataset:



Moro, S., Rita, P., \& Cortez, P. (2014). Bank Marketing \[Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306

Licensed under CC BY 4.0.

