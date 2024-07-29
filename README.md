This mini-project predicts diabetes using a KNN classifier with health metrics such as Glucose, Blood Pressure, Skin Thickness, BMI, and Insulin. The model classifies individuals into “Not diabetic” and “Diabetic.”

Data Preparation: Replaced zeros in specific columns with the mean to handle missing values.
Feature Scaling: Standardised features to ensure consistency.
Model Training: Used k-NN with 5 neighbors and Euclidean distance.
Evaluation: Achieved an accuracy of 74.68% and an F1 score of 67.77%.

To improve model accuracy, you could consider using a larger dataset. You could also tune hyperparameters by experimenting with different k values, or using gridsearch.

This is a recreation of a popular basic machine learning project. To run locally, pip install pandas numpy scikit-learn matplotlib and execute the provided code.
