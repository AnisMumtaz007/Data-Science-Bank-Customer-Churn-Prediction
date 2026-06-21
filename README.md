# Bank Customer Churn Prediction Artificial Neural Network (ANN)
Objective

Predict whether a customer will leave the bank using an Artificial Neural Network (ANN).

Dataset
Churn_Modelling.csv
Total Samples
10,000
Target Variable
Exited
0 = Customer Stayed
1 = Customer Churned
Data Preprocessing
Removed Columns
RowNumber
CustomerId
Surname
Feature Engineering
One-Hot Encoding:
Geography
Gender
Scaling
StandardScaler()

applied to all numerical features.

ANN Architecture
Input Layer

→ Dense(16, ReLU)

→ Dense(8, ReLU)

→ Dense(1, Sigmoid)
Hyperparameters
Parameter	Value
Optimizer	Adam
Loss	Binary Crossentropy
Epochs	50
Batch Size	32
Results
Metric	Value
Accuracy	~85–86%
Training Loss	0.66 → 0.34

Evaluation includes:

Confusion Matrix
Precision
Recall
F1-Score
Classification Report

The ANN successfully learns customer behavior patterns and achieves competitive churn prediction performance.
