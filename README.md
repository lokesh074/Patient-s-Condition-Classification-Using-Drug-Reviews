# Patient-s-Condition-Classification-Using-Drug-Reviews

Dataset -- https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29 <br />
<br /> we have demonstrated the application of Natural Language Processing in classifying patients condition
based on their reviews on drugs. <br />
We used BoW and TFIDF technique  to check which technique would be better <br />

# WorldCloud = 
Here we used World Cloud for Common conditions like (Birth Control, Depression, High Blood Pressure, Diabetes, Pain, Anxiety)<br />
Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. Significant textual data points can be highlighted using a word cloud. Word clouds are widely used for analyzing data from social network websites.
# TF_IDF = 
TF-IDF stands for term frequency-inverse document frequency and it is a measure, used in the fields of information retrieval (IR) and machine learning, that can quantify the importance or relevance of string representations (words, phrases, lemmas, etc) in a document amongst a collection of documents.
# BoW = 
Bag of Words (BOW) is one way of modeling text data for machine learning. This is the basic form of representing the text into numbers. Tokenized sentence is represented by an array of frequency of each word from the dictionary in the sentence <br />

<br /> Bow fits for small dataset .


# Machine Learning Model 
we used Naive Bayes & PassiveAggressiveClassifier <br />
MuitlinomialNB used for NLP applications that we have used in this Project

# PassiveAggressiveClassifier() 
The passive-aggressive algorithms are a family of algorithms for large-scale learning. They are similar to the Perceptron in that they do not require a learning rate. However, contrary to the Perceptron, they include a regularization parameter C.
<br />
<br />
For classification, PassiveAggressiveClassifier can be used with loss='hinge' (PA-I) or loss='squared_hinge' (PA-II). For regression, PassiveAggressiveRegressor can be used with loss='epsilon_insensitive' (PA-I) or loss='squared_epsilon_insensitive'
C (float), default=1.0
Maximum step size (regularization). Defaults to 1.0.
<br />
<br />
Regularization refers to techniques that are used to calibrate machine learning models in order to minimize the adjusted loss function and prevent overfitting or underfitting. Using Regularization, we can fit our machine learning model appropriately on a given test set and hence reduce the errors in it.
![Screenshot (638)](https://user-images.githubusercontent.com/91384498/210129656-6291c600-5864-4ddc-8930-9abd3ced09be.png)


