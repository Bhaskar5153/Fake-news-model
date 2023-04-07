# Fake-news-model
ML model for identifying legit or fake news 


############################################################

This is a very simple classification problem. The dataset has two features called title and text and dependent variable called Label.
We drop the title feature as we want to train our model only on the actual context. We check the count of each label and found that dataset is pretty balanced. 
now, we need to perform the data preprocessing, but the "Count vector" from SKlearn takes care of that for us. 


Count vectorizer: it is also called "BAG OF WORDS". it converts text documents into matrix. it takes care of all the preprocessing techniques on the data.
for more information, you can click here: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html

Prediction Model - Decision Tree

Decision tree is a supervised machine learning algorithm that can predict the target value by learning the data features.

for more information, you can refer to online documentation: https://scikit-learn.org/stable/modules/tree.html

In the dataset, label 0 = Fake, 1 = Legit



