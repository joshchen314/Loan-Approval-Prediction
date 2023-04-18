# Loan-Approval-Prediction
# Introduction
This project is called "Loan Approval Classifier" using a loan dataset with 9,500 rows and 14 columns. The project's goal is to predict whether a loan will not be paid back rather than if a loan is paid back. Key steps in the project include:

1. Data exploration and preprocessing: The data is cleaned and preprocessed, including handling missing values, removing unnecessary columns, encoding categorical features, and scaling numerical features.

1. Handling class imbalance: The SMOTE technique is applied to balance the classes in the training data.

1. Splitting the data: The dataset is split into training and testing sets.

1. Model training and selection: The RandomForestClassifier and CatBoostClassifier are combined into a custom classifier called CombinedClassifier. A Pipeline object is created, and hyperparameters are tuned using GridSearchCV. Evaluation metrics such as accuracy, precision, recall, and F1 score are used to assess the models' performance.

1. Saving the model: The best-performing model is saved to disk using the joblib library.

1. Creating a web app: A Gradio web app is built to allow users to interact with the trained model and make predictions.

1. Deployment: The web app is deployed on a loveable space, Hugging Face.

TIP: for deploying the application app, preprocessing data step is very important that the amounts of features in the model steps and the web app step should be the same. 

[View code on Github]

(https://github.com/joshchen314/Loan-Approval-Prediction)
