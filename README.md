# Phishing-Website-Detection

A Machine Learning Model to detect Malicious URLs and Phishing Attempts. The ML Model is trained and tested on a Dataset with 11470 urls with 50% Phishing and 50% Legitimate URLs , The Model is an Ensemble Model based on several ML Algorithms such as K-Nearest Neighbours (KNN) , Decision Tree (DT) , Logistic Regression (LR) with soft voting .

Before Running the Code in Local Machine makesure you've the listed Libraries Present
- Pandas
- warnings
- plotly
- sklearn
- numpy
- re
- tldextract
- ipaddress
- urlilib.parse
- requests
- bs4

Steps to Train and Run this Model
## Setup the Environment
Ensure you have the following libraries installed. You can install them using pip:

pip install pandas plotly scikit-learn numpy tldextract ipaddress requests beautifulsoup4

## Loading and Preprocessing the Data
You need to load the dataset and preprocess it before feeding it into the model.

## Training the Ensemble Model
We train an ensemble model using KNN, Decision Tree, and Logistic Regression with soft voting.

## Evaluating the Model
Evaluate the Model with Training and Testing Accuracy with Confusion Matrix
