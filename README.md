# credit-risk-classification


Overview of the Analysis


The purpose of this analysis is to develop and evaluate a machine learning model for loan risk prediction using lending data from a peer-to-peer lending services company.

The objective is to build a model that can effectively identify the creditworthiness of borrowers.



Results:

Accuracy: 99%
Balanced Accuracy: 94%
+ Precison
    - 0 (healthy loan): 100%
    - 1 (high-risk loan): 87%
+ Recall
    - 0 (healthy loan): 100%
    - 1 (high-risk loan): 89%
+ F1-score
    - 0 (healthy loan): 1.00
    - 1 (high-risk loan): 0.88
+ Support
    - 0 (healthy loan): 18,759
    - 1 (high-risk loan): 625


Summary

The model excelled in identifying healthy loans with a precison and reccall of 100%. This means the mnodel made no false positive predictions for healthy loans. For high risk loans the model got a precison of 87% and recall of 89%. this indicates a good balance between identifying high risk loans and minimizing the number of false negatives.

The models ability to achieve 100% precision for healthy loans ensures that only truly creditworthy borrowers are approved. The models high recall for high risk loans ensures the company indentifies a good portion of risky borrowers, which will help lower and potential losses to the company. With a accuracy of 99% and balanced accuracy of 94% we can see that the model is very good at loan risk prediction.

Based on the analysis results, I would reccomend the the model for loan risk prediction to the company.