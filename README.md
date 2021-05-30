# CreditCard_Lead_Prediction

This was created as a part of the Analytics Vidhya Job-a-thon in May 2021 to predict if the customer is interested in credit card or not  by analyzing the data set.  

In this project the outcome is Is_Lead 0[Not Interested] or 1 [Interested]

We are going to look at a Data set which contains 10 independent variables [object , int & float type] & 1 Target variable [int type].

6 features have different categories, however we created columns under one hot encoding. For ID object, we dropped it as its unique identifier.

All features  are already scaled using standard scaler.

Did Feature importance also to understand which among them are important.
Analyzed different algorithms to see which one gives best ROC AUC value
Here is Ensemble Bagging Classified ROC curve
![Ensemble Bagging Classified ROC curve](https://github.com/amar-chakka/CreditCard_Lead_Prediction/blob/e204e8eb03d6b9b965b451a1c0b01d764fb42561/Ensemble_ROC_AUC%20Curve.png?raw=true)


Here is the Random Forest Classifier ROC Curve
![RFC Curve](https://github.com/amar-chakka/CreditCard_Lead_Prediction/blob/e204e8eb03d6b9b965b451a1c0b01d764fb42561/RFC_ROC_AUC%20Curve.png?raw=true)

Here is XGB Classifier ROC Curve
![XGB Curve](https://github.com/amar-chakka/CreditCard_Lead_Prediction/blob/e204e8eb03d6b9b965b451a1c0b01d764fb42561/XGB_ROC_AUC%20Curve.png?raw=true)

As shown above, based on ROC AUC value, classifier was evaluated with 0.78 being best value.

Conclusion:
•I analyzed the characteristics and distribution of data in brief.
•I investigated in-depth the features which to retain and which to discard.
•I performed model development by using different classifiers and hyper parameters.
•I observed mixed results as we started experimenting with different combinations.
•This model will help the bank in predicting the customers with a metric of ROC AUC= 0.78 [which was based on FPR & TPR] 

To check out my notebook, please click [here](https://github.com/amar-chakka/CreditCard_Lead_Prediction/blob/e204e8eb03d6b9b965b451a1c0b01d764fb42561/CreditCard_LeadPrediction.ipynb).
