I was hired by the Titanic Company and they want me to build a predictive model using the passenger data to predict: what sorts of people were more likely to survive?

I'm a beginner in Machine Learing. This is my first project on Kaggle, and I'm grateful to @GUNES EVITAN and @Erik Bruin for introducing me to this captivating journal in the competition. One of the most significant lessons I've gained from this experience is the art of feature engineering.

I've observed that when handling missing data, particularly in features like "Cabin", the way we classify the missing data into different groups can significantly influence the final outcomes.

In terms of model selection, I opted for two models: Random Forest and SVM. Why?

Random Forest stands out as an ensemble learning technique that amalgamates multiple decision trees for prediction, ensuring high robustness. It excels in handling imbalanced data, coping with missing values, and typically carries a lower risk of overfitting compared to individual decision trees. Moreover, it offers a direct assessment of the importance of each feature, which is invaluable for comprehending the dataset and guiding feature engineering efforts.

SVMs, on the other hand, demonstrate effectiveness in high-dimensional spaces, making them particularly suitable for problems with a large number of features
