# Credit-Card-Fraud-Detection
Introduction:
Credit card fraud detection is a crucial task in the financial sector to prevent unauthorized transactions and minimize financial losses. This project focuses on building a machine learning model to detect fraudulent credit card transactions using a dataset of historical transactions.
Explanation:
The project follows a typical machine learning workflow:
Data Collection: The dataset used in this project consists of historical credit card transactions, which include both fraudulent and non-fraudulent transactions. The dataset is typically imbalanced, with fraudulent transactions being a small minority.
Data Preprocessing: This step involves cleaning the data, handling missing values, and scaling features. Additionally, techniques such as SMOTE (Synthetic Minority Over-sampling Technique) are used to address class imbalance.
Feature Selection: Relevant features are selected using techniques like correlation analysis and feature importance evaluation to improve the model's performance.
Model Building: Various machine learning algorithms are employed to build the fraud detection model. These include Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
Model Evaluation: The models are evaluated using appropriate metrics such as accuracy, precision, recall, F1-score, and the ROC-AUC curve to assess their performance in detecting fraudulent transactions.
Outcomes:
The Logistic Regression classifier performed the best. The key reasons for this conclusion are:

Highest Accuracy: The Logistic Regression model achieved an accuracy of 99.95%, which is the highest among the evaluated classifiers.
High F1-Score: It also achieved a high F1-Score of 0.8561, indicating a good balance between precision and recall.
AUC-ROC: The AUC-ROC score of 0.9121 for Logistic Regression is significantly high, demonstrating its effectiveness in distinguishing between fraudulent and non-fraudulent transactions.
Balanced Performance: The classification report shows that Logistic Regression had a good balance in precision and recall for the fraud class (Class 1), which is critical in fraud detection scenarios.
Summary of the Logistic Regression model's performance:
Accuracy: 99.95%
Precision: 0.89
Recall: 0.82
F1-Score: 0.8561
AUC-ROC: 0.9121
Therefore, the Logistic Regression classifier is the best performing model for this credit card fraud detection project.
Feature Importance:
The feature importance analysis identified that certain features, such as V14, V10, V12, V17, V4, and Amount, are significant indicators of fraud.

Imbalance Handling:
The use of SMOTE (Synthetic Minority Over-sampling Technique) successfully addressed the class imbalance issue, resulting in improved model performance across all classifiers.

Conclusion:
The project demonstrates the effectiveness of machine learning models in detecting credit card fraud. By leveraging techniques such as feature selection and class imbalance handling, the model achieved high accuracy and reliability. This approach can be integrated into real-world systems to enhance fraud detection capabilities and protect financial assets.
Further improvements can be made by exploring advanced algorithms, incorporating additional data sources, and continuously updating the model with new transaction data to maintain its effectiveness over time.
