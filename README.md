# Fraudulent Transactions Detection

The purpose of this project is to train and test a binary classifier to detect fraudulent transactions using Random Forest and Naive Bayes approaches. 
The initial training dataset contains 227,845 rows and 31 columns, including: Time, 27 anonymized features, Amount, and Class (the target variable). 
The Class column has values 0 for a normal transaction and 1 for a fraudulent transaction. The dataset is highly imbalanced, with 227,451 normal transactions and only 394 fraudulent ones. 

This project includes two scripts: one for training a binary classifier and one for testing it. Additionally, it contains the initial dataset, trained model by itself and a detailed report that describes the entire training process and results.

We begin by balancing the dataset, then investigate and identify the most impactful features using a Random Forest model. 
Based on the selected features, we train a Naive Bayes binary classifier. 

**The final Naive Bayes model on unseen data achieves 95% accuracy on the training set and 97% accuracy on the test set.** The classifier performs better on the test set than on the training set, which suggests that it generalizes well to unseen data. 
This indicates that the model has not overfitted and is effectively capturing the underlying patterns required to detect fraudulent transactions.
