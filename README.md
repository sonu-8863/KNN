#Heart attack possibility Prediction using KNN

This project focuses on predicting heart disease using the K-Nearest Neighbors (KNN) algorithm. The dataset was loaded using Pandas, and the target variable was separated from the input features for model training.

Data preprocessing included feature scaling using StandardScaler, which is essential for distance-based algorithms like KNN. The dataset was then split into training and testing sets using train_test_split.

Multiple K values (k = 3, 5, 7, 9) were tested to find the optimal number of neighbors. Further, hyperparameter tuning was performed using GridSearchCV with cross-validation to select the best model based on recall score.

 Model Performance (Best Model)
Accuracy: 91.80%
Precision: 93.54%
Recall: 90.62%
⚙️ Key Techniques Used
Feature Scaling (StandardScaler)
KNN Algorithm (distance-based learning)
Hyperparameter Tuning (GridSearchCV)
Cross-validation for model selection
Performance evaluation (Accuracy, Precision, Recall)
