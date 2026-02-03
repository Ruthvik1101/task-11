Task 11: SVM – Breast Cancer Classification 

Report 

 

Objective 

The objective of this task is to develop an effective machine learning model to classify breast cancer tumors as malignant or benign using the Support Vector Machine (SVM) algorithm. The task also aims to compare different SVM kernels, optimize model performance using hyperparameter tuning, and evaluate the final model using standard classification metrics 

Dataset description: 

The Breast Cancer Wisconsin dataset from sklearn.datasets was used in this task. 
It contains 569 samples with 30 numerical features, which describe characteristics of cell nuclei present in breast cancer biopsies. 
The target variable has two classes: 

0: Malignant 

1: Benign 

Methodology: 

The methodology for this task involved using the Breast Cancer Wisconsin dataset to build a classification model using Support Vector Machine (SVM). The dataset was first divided into training and testing sets in an 80:20 ratio to ensure unbiased evaluation. Since SVM is sensitive to feature scale, the data was standardized using StandardScaler. Two SVM kernels, linear and RBF, were implemented to compare performance. Hyperparameter tuning was carried out using GridSearchCV to identify the optimal values of parameters such as C and gamma. The best-performing model was selected based on cross-validation accuracy. Finally, the optimized model was evaluated on the test data using accuracy score, confusion matrix, and classification metrics. 

Conclusion 

This task demonstrates that Support Vector Machines, particularly with the RBF kernel, are highly effective for breast cancer classification. Feature scaling and hyperparameter tuning played a crucial role in improving performance. The final model provides reliable predictions and can be used as a supportive tool for early breast cancer diagnosis. 

 
