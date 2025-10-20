# Credit Card Customer Churn Prediction using ANN

This project uses an Artificial Neural Network (ANN) to predict customer churn in a credit card dataset. It demonstrates how deep learning can be applied to business analytics problems, helping financial institutions proactively retain customers.

## 🔍 Problem Statement
Customer churn is a critical issue for banks and credit card companies. By predicting which customers are likely to leave, businesses can take targeted actions to improve retention. This notebook builds a classification model using Keras and TensorFlow to identify churn risks based on customer behavior and demographics.

## 📊 Dataset
- Source: Kaggle Dataset (`credit-card-customer-churn-prediction`)
- Features include: Credit score, tenure, balance, number of products, active status, estimated salary, etc.
- Target: `Exited` (1 = churned, 0 = retained)

## 🧠 Model Architecture
- Framework: Keras with TensorFlow backend
- Type: Feedforward ANN (Sequential model)
- Layers:
  - Input layer with normalized features
  - Hidden layers with ReLU activation
  - Output layer with sigmoid activation for binary classification
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Metrics: Accuracy

## 📈 Performance
- Achieved high accuracy on test data
- Evaluated using confusion matrix and classification report
- Model generalizes well across unseen data

## 🛠️ Key Steps
1. Data preprocessing (scaling, encoding)
2. Model building with Keras
3. Training and validation
4. Evaluation and interpretation
5. Deployment-ready structure for GitHub

## 📦 Dependencies
```bash
tensorflow
keras
scikit-learn
pandas
numpy
matplotlib
