# Spam-or-non-spam-classifiers--non-spam
An Email text classifier in Python for classification with discrete features using classification algorithms of machine learning  which is Naïve Bayes classifier especially Multinomial NB to detect if a given mail or message is spam or ham (not spam). 

# Objective 
For a dataset containing various Subjects of emails which are classified as either Spam or as Ham (Not Spam). We are required to predict whether given an Email subject whether it is Spam or Ham.

# Procedure 

1. Data Cleaning
2. Pre processing
3. Feature Extraction
4. Model training and evaluation

# Description 

**Spam or Ham Classifier using Naive Bayes Classifier**

The **Spam or Ham Classifier** project aims to develop a model that classifies email messages as either spam or ham (non-spam) using the Naive Bayes classifier. The project focuses on leveraging text-based data from emails and applying machine learning techniques to automatically categorize emails into the appropriate class.

### Project Description:

- **Data Processing and Preparation**: The project starts by processing and preparing the email text data. This involves cleaning the data to remove unnecessary characters, punctuation, and whitespace, as well as converting the text data to lowercase for consistency.

- **Feature Extraction**: Once the data is prepared, the project uses the `CountVectorizer` from the `sklearn.feature_extraction.text` module to transform the email text into a bag-of-words representation. This step converts the email text data into a numerical format that can be used as input for the classifier.

- **Model Training**: The classifier of choice for this project is the Naive Bayes classifier, specifically `MultinomialNB` from `sklearn.naive_bayes`. The project trains the model on the processed data, using the bag-of-words representation and labels (spam or ham) to learn the patterns in the data.

- **Model Evaluation**: To assess the performance of the classifier, the project uses a confusion matrix to evaluate the model's ability to classify emails as spam or ham. The confusion matrix provides metrics such as precision, recall, and F1-score for each class, allowing the team to gauge the model's accuracy and overall effectiveness.

- **Prediction and Results**: Once the model is trained and evaluated, it can be used to predict whether new emails are spam or ham. The project's ultimate goal is to achieve a high level of accuracy in classifying emails, helping users manage their inboxes effectively and reduce the impact of spam.

The **Spam or Ham Classifier** project leverages powerful machine learning techniques to address the practical problem of email spam detection. By using a Naive Bayes classifier in combination with CountVectorizer and evaluating the model with a confusion matrix, the project aims to deliver an efficient and accurate spam detection system.
