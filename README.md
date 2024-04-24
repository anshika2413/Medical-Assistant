# Medical-Assistant
A Medical Assistant that helps users to find about their disease on the basis of their symptoms.

# Decision Tree:
1) A decision tree is a flowchart-like structure where each internal node represents a "test" on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label.
2) Decision trees are intuitive and easy to interpret, making them useful for understanding the logic behind classification decisions.
However, they can be prone to overfitting, especially with complex datasets. # Bagging Classifier:
3) Bagging (Bootstrap Aggregating) is an ensemble learning technique that combines multiple classifiers trained on different subsets of the training data.
4) In a bagging classifier, multiple decision trees (or other base classifiers) are trained independently on random subsets of the training data with replacement.
5) Bagging helps reduce variance and improve generalization by averaging the predictions of multiple models.
6) Random Forest is a specific implementation of a bagging classifier using decision trees as the base classifiers.
   
# Support Vector Machine (SVM):
1) SVM is a powerful supervised learning algorithm used for classification, regression, and outlier detection.
2) SVM works by finding the optimal hyperplane that best separates the data points of different classes in a high-dimensional space.
3) It is effective in high-dimensional spaces and is memory efficient since it only uses a subset of training points (support vectors) to define the decision boundary.
# Random Foresr: 
1) Random Forest is an ensemble learning method that combines multiple decision trees to create a more robust and accurate model.
2) Unlike a single decision tree, which can overfit on the training data, Random Forest reduces overfitting by averaging the predictions of many trees trained on random subsets of the data.
3) It introduces randomness both in the selection of data samples (bootstrap samples) and the features considered at each split, leading to diverse trees that collectively provide better generalization.
4) Random Forest is known for its ability to handle high-dimensional data, large datasets, and maintain good performance without extensive hyperparameter tuning.

# How to run the ML Model:
1) Upload the dataset files ie. Testing.csv and Training.csv on google drive.
2) Open the **disease-prediction.ipynb** file on google colab
3) Give the permission to googlecolab to access the files from google drive.
4) Now you can run the model and it will show its output line by line. 
   
