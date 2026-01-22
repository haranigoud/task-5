Objective :

The objective of this task is to understand model evaluation fundamentals by:
Splitting data into training and testing sets
Training a simple machine learning model
Evaluating the model using standard metrics

Dataset ;

Heart Disease Dataset
Each row represents a patient
Features include medical attributes

Target column :

target = 1 → Heart disease present
target = 0 → No heart disease

Tools & Libraries Used :

Python
Pandas
Scikit-learn

Steps Performed :

Load the Dataset :

The dataset is loaded using Pandas and separated into:

Features (X)
Target (y)

Train-Test Split :

The dataset is split into :

80% Training Data
20% Testing Data

Why split data?

Training data is used to train the model
Testing data checks performance on unseen data
Helps avoid overfitting

 Model Training :

Logistic Regression is used
Suitable for binary classification problems
Simple and easy to interpret

 Prediction :

The trained model predicts outcomes on the test dataset.

Evaluation Metrics :

The following metrics are calculated :

Accuracy :
Measures overall correctness of the model

Precision :
Measures how many predicted positives are actually correct

Recall :
Measures how many actual positives were correctly identified

Confusion Matrix :

True Positives
True Negatives
False Positives
False Negatives

Results :

The model outputs :

Accuracy score
Precision score
Recall score
Confusion Matrix
These metrics help understand how well the model performs.