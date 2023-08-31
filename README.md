# SMS-Spam-Classifier

Welcome to the Email Spam Classifier project! This project is designed to classify emails as either spam or legitimate using machine learning techniques and natural language processing (NLP). By harnessing the power of NLP, the classifier can analyze the text content of emails to distinguish between unwanted spam and legitimate messages.

Overview
In an era of overwhelming email traffic, filtering out spam is crucial for maintaining productivity and security. This project tackles the challenge of automating the identification of spam emails. By training a machine learning model on a dataset of labeled email messages, we aim to create a tool that can accurately classify incoming emails as spam or non-spam.

Features
Data Preprocessing: Email content often contains HTML tags, special characters, and irrelevant information. Our project includes data preprocessing steps that clean and tokenize the text, ensuring the best possible input for our models.

TF-IDF Vectorization: Transforming text data into a numerical format is essential for machine learning. We utilize Term Frequency-Inverse Document Frequency (TF-IDF) vectorization to convert text content into a format that can be used by various machine learning algorithms.

Model Selection: We explore a variety of machine learning algorithms for email classification, including Naive Bayes, Support Vector Machines, and Logistic Regression. The aim is to find the algorithm that offers the best balance between accuracy and efficiency.

Performance Metrics: Evaluating the effectiveness of the classifier is crucial. We employ metrics such as accuracy, precision, recall, and F1-score to assess the model's performance on both training and test data.

# Clone this repository to your local machine.
git clone https://github.com/samagra44/email-spam-classifier.git
cd email-spam-classifier

# Create a virtual environment (recommended) and activate it.
python3 -m venv venv
source venv/bin/activate

# Install the required dependencies using pip.
pip install -r requirements.txt

The dataset used for training and evaluation is sourced from "https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset".This dataset contains a collection of labeled email messages, where each email is marked as spam or ham.

# Model Training
The model training process consists of the following steps:

1.Loading and preprocessing the email dataset.
2.Applying TF-IDF vectorization to transform the text data.
3.Splitting the data into training and testing sets.
4.Training multiple machine learning models on the training data.
5.Evaluating the models using various performance metrics.

# Contributing
Contributions to this project are highly encouraged! Feel free to open issues and submit pull requests for enhancements, bug fixes, or additional features.
