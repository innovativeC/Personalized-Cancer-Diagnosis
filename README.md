# Personalized-Cancer-Diagnosis
The objective of the analysis was for a given gene, variation and text, using text to determine which of the
classes does this gene and variation fall into. It was a multi-class classification problem with classes ranging from 1-9.
Used Calibrated Classifier on top of effective algorithms like Naive Bayes and Logistic Regression to predict the
classification a given gene, variation and text. Performed data optimization tasks such as data mining, text preprocessing 
and exploratory data analysis which consisted of creating a random model with a metric of log loss to determine the worst 
log loss of the given data using pandas, numpy, sklearn. Performed univariate analysis on each feature i.e., 
Gene, Variation and Text using one-hot encoding, Calibrated Classifier and Logistic Regression to find the most important 
feature and to find the stability of each feature. Finally stacked the three features into train, cross validation and 
test data frames and then applied Naive Bayes and Logistic Regression on the complete data to check which model worked 
the best by comparing the log loss, confusion, precision, recall matrices and the misclassified points with the random model.
