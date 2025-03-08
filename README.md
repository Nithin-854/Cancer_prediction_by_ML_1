# Cancer_prediction_by_ML_1
This Python program uses Random Forest Classification to predict the likelihood of cancer based on user-inputted medical parameters. The model is trained on a dataset and optimized using RandomizedSearchCV for better accuracy.


📌 Overview

This project is a machine learning-based cancer prediction system that uses Random Forest Classification to predict the likelihood of cancer based on user-inputted medical parameters. It is trained on a dataset and optimized using RandomizedSearchCV for better accuracy. The model provides a percentage probability of cancer based on the given input.



🚀 Features

✅ Accepts user input for medical parameters and predicts cancer probability.✅ Uses Random Forest Classifier for accurate predictions.✅ Handles class imbalance using SMOTE (Synthetic Minority Oversampling Technique).✅ Hyperparameter tuning with RandomizedSearchCV.✅ Feature scaling for improved performance.✅ Visualizes the confusion matrix for model evaluation.



📂 Dataset

The dataset should be in CSV format (cancer_prediction.csv).

It must contain a diagnosis column as the target variable (1 = Cancer, 0 = No Cancer).

The rest of the columns should be medical features used for prediction.

🛠 Installation

Clone this repository or download the code.

Install required dependencies:

pip install numpy pandas seaborn matplotlib scikit-learn imbalanced-learn

Ensure you have the dataset (cancer_prediction.csv) in the same directory.



📜 Usage

Run the script:

python cancer_prediction.py

The script will train the model and display:

Model Accuracy

Classification Report

Confusion Matrix (visualized using seaborn)

Enter the required feature values when prompted.

The model will output the probability (in %) of having cancer.



📌 Code Explanation

Load the dataset from cancer_prediction.csv.

Split features (X) and target (y), then apply a train-test split.

Handle class imbalance using SMOTE to balance positive and negative cases.

Scale the features using StandardScaler.

Perform hyperparameter tuning with RandomizedSearchCV to optimize the Random Forest model.

Train the best model and evaluate its accuracy.

Get user input for real-time prediction.

Predict and display the probability of cancer.
