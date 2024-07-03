# Spam-sms-detection
Steps involved in creating the model are :

1. Data Cleaning
2. EDA
3. Data Preprocessing
4. Model Building

Model used is : The BernoulliNB model. It is a type of Naive Bayes classifier specifically designed for binary/boolean features. It's part of the family of probabilistic classifiers based on Bayes' theorem with strong (naive) independence assumptions between the features. The BernoulliNB classifier is particularly suited for discrete data, where the features are binary (0 or 1).

About the dataset : The dataset contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.
