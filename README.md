# Sure-Tomorrow-Insurance
![image](https://user-images.githubusercontent.com/115895428/216845770-2f10be90-cbb7-41c9-9efe-b263fad696b0.png)

## Skills Demonstrated
    Pandas
    EDA
    Matrices
    Sklearn
    Binarizer
    Data Obfuscation
    F1 score, Accuracy score, AUC-ROC, R2, MSE
    KNeighbors Classifier
    Decision Tree Classifier
    Random Forest Classifier
    Cross Validation
    Plotly Express


## Purpose
The Sure Tomorrow insurance company wants to solve several tasks with the help of Machine Learning and we are asked to evaluate that possibility.

- Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
- Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a prediction model do better than a dummy model?
- Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without breaking the model from the previous task. It's necessary to develop a data transformation algorithm that would make it hard to recover personal information if the data fell into the wrong hands. This is called data masking, or data obfuscation. But the data should be protected in such a way that the quality of machine learning models doesn't suffer. You don't need to pick the best model, just prove that the algorithm works correctly.

## Conclusions
We trained a model that would return similar customers for a given one. This model was calculated while scaled and unscaled, using euclidean and manhattan distances. Then, we created a dummy model to test the f1 scores of different probability values. We found the dummy model to be less accurate than the classification model we built, using both original and scaled data. After, a linear regression model was built with matrix operations. The evaluation metrics of RMSE and R2 score were measured, and then compared to a linear regression model on the obfuscated data. We concluded that obfuscation did not alter the accuracy of the model, as the RMSE and R2 metrics were the same before and after obfuscation. Overall, we have provided results that suggest a very accurate prediction as to whether a customer will, or will not receive insurance benefits. This is more accurate than trying to predict the actual number of insurance benefits a customer will receive. Consequently, we suggest Sure Tomorrow use the more accurate classification model over the regression model.  


## [Web Notebook](https://jodiambra.github.io/Sure-Tomorrow-Insurance-Benefits-Predictions/)
