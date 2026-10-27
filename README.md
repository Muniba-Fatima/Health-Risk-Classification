# Health-Risk-Classification
## Conclusion

In this project, a Health Risk Classification system was developed using machine learning to predict diabetes outcomes based on patient health indicators. The Pima Indians Diabetes Database was used to train and evaluate two classification models: Support Vector Machine (SVM) and Decision Tree.

Data preprocessing was performed to prepare the dataset for machine learning. Zero values in selected medical measurements were treated as missing values, and median imputation was used to handle them. The dataset was divided into training and testing sets, with 80% of the data used for training and 20% used for testing. StandardScaler was applied to the SVM model to standardize the numerical features.

Both machine learning models were trained and tested using the same dataset split. Their performance was evaluated using accuracy, precision, recall, F1-score, and confusion matrices. Visualizations were also created to understand the distribution of diabetes outcomes, compare glucose levels, and display the performance of the models.

The project also examined the possibility of overfitting by comparing training accuracy with testing accuracy. A Decision Tree with a limited depth was used to help control model complexity. Comparing the two models helped demonstrate how different machine learning algorithms can produce different results on the same classification task.

Overall, this project provided practical experience in data preprocessing, data visualization, supervised machine learning, model evaluation, and performance comparison. It demonstrated how machine learning can be applied to health-related data to identify patterns associated with diabetes outcomes.

However, the predictions are intended for educational purposes only and should not be used as a substitute for professional medical diagnosis. The model's performance on this dataset does not guarantee reliable predictions for other populations or real-world patients.

In conclusion, the project successfully demonstrated the implementation and comparison of two machine learning classification models and provided a foundation for understanding how machine learning can support health risk analysis.
