# Credit-Card-Fraud-Detection
Detecting if a credit card transaction is legitimate or fraud using ML that will help banks to put proactive monitoring and fraud prevention mechanisms in place.

This project aims to detect credit card fraud using machine learning techniques. It starts by importing necessary libraries like NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn. The dataset consists of credit card transactions, where each transaction has various features like time, amount, and V1-V28, along with a binary label indicating whether the transaction is fraudulent or not.

The data is explored to understand its distribution and characteristics. The class distribution shows a balanced dataset with equal proportions of fraudulent and valid transactions. Descriptive statistics are computed to gain insights into the data, such as mean, standard deviation, and quartile values.

![image](https://github.com/ComfyJ/Credit-Card-Fraud-Detection/assets/104603037/f9348ff3-5462-4033-96cd-2811c99ff936)


Further analysis involves examining the correlation between features using a heatmap, indicating any potential relationships between variables. Then, the dataset is divided into features (X) and the target variable (Y).

![image](https://github.com/ComfyJ/Credit-Card-Fraud-Detection/assets/104603037/9efb38d2-a34f-4a53-b36c-e869b12d12e2)

The Random Forest Classifier is chosen as the model for fraud detection. The model is trained on the training data and evaluated using various metrics such as accuracy, precision, recall, F1-score, and Matthews correlation coefficient. The evaluation results show high performance in detecting fraud, with very high scores across all metrics.

Finally, the confusion matrix is plotted to visualize the performance of the model in classifying transactions as normal or fraudulent. The confusion matrix provides a detailed view of the model's predictions compared to the actual labels.
![image](https://github.com/ComfyJ/Credit-Card-Fraud-Detection/assets/104603037/284e4091-8939-4bbb-abcb-324686f39b48)


Data Exploration: The project begins by exploring the dataset to understand its structure, distribution, and characteristics. This involves examining the class distribution to ensure the dataset is balanced between normal and fraudulent transactions and computing descriptive statistics to gain insights into the data's attributes.

Model Building and Training: After data exploration, the dataset is prepared for model training by dividing it into features (X) and the target variable (Y). The Random Forest Classifier model is then trained on the prepared data, where it learns patterns and relationships from the features to classify transactions.

Model Evaluation: Once trained, the model is evaluated using a separate portion of the dataset reserved for testing. Various evaluation metrics such as accuracy, precision, recall, F1-score, and Matthews correlation coefficient are calculated to assess the model's performance in detecting fraudulent transactions.

Visualization of Results: The project visualizes the model's performance using a confusion matrix, which provides a detailed overview of the model's predictions compared to the actual class labels. Additionally, a heatmap of the correlation matrix is plotted to identify any potential relationships between features.

Overall, the project aims to develop an effective fraud detection system using machine learning techniques and evaluate its performance in accurately identifying fraudulent credit card transactions.
## Conclusion
The conclusion of the project using machine learning techniques is that the Random Forest Classifier model shows promising results in detecting fraudulent credit card transactions.

High Accuracy: The model achieves a high accuracy score, indicating that it correctly classifies the majority of transactions as either legitimate or fraudulent.

High Precision and Recall: The precision and recall scores are also high, suggesting that the model effectively identifies fraudulent transactions while minimizing false positives.

High F1-Score: The F1-score, which balances precision and recall, is also high, indicating a good balance between identifying fraudulent transactions and avoiding misclassifications.

High Matthews Correlation Coefficient (MCC): The MCC score, which considers both true and false positives and negatives, is high, further confirming the model's effectiveness in binary classification tasks.

Confusion Matrix Visualization: The confusion matrix provides a visual representation of the model's predictions compared to the actual class labels, showing a strong agreement between predicted and actual values.

Correlation Matrix Analysis: The heatmap of the correlation matrix helps identify potential relationships between features, providing insights into the dataset's underlying patterns.

Overall, the project demonstrates that machine learning techniques, particularly the Random Forest Classifier model, can be successfully applied to detect fraudulent credit card transactions with high accuracy and reliability. However, further testing and validation may be necessary to assess the model's performance on unseen data and ensure its robustness in real-world applications.
