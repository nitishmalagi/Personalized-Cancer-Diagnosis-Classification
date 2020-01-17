# Personalized-Cancer-Diagnosis-Classification

The goal of this project is to classify the given genetic variations/mutations based on evidence from text-based clinical literature. This is a Multi class classification problem as there are nine different classes a genetic mutation can be classified into.

The text feature is pre-processed initially be removing the stopwords. Then, the data is split into train test & CV sets and the distribution of classes in all the sets is analyzed using visualizations. To compare the models that are built later, a random model is built and it's Log-loss is calculated. 

Further, univariate analysis is done on all the features to estimate how good a feature is in predicting y_i. One-hot encoding and response encoding are used for feature engineering and models are built using Naive Bayes, K-NN, Linear Support Vector Machines and Random Forest Classifier.
