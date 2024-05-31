Sentiment analysis is a branch of Natural Language Processing (NLP) which focuses on 
extracting and recognizing emotional content from written text and divide thoughts as neutral, 
positive, or negative based on the level of emotion shown in the text (Liu, 2015). This is a 
necessary tool for determining the needs of the costumers and the perspective about an item 
and provided services on e-business sites like Amazon. To gain valuable intuition into their 
customer’s thinking the best option is to analyse the buyer’s reviews and star ratings. This kind 
of information can lead to better decision-making for marketing campaigns, customer support 
and product development. 

Methodology 
The analysis of Amazon review dataset can include various crucial steps. At first, the provided 
dataset is examined and organize by preprocessing techniques. The Exploratory Data Analysis 
(EDA) methods (sentiment analysis, feature engineering, topic modelling) and and 
visualization approaches are utilized to examine sentiment patterns across temporal 
dimensions.  
Text preprocessing methods are used to improve the quality of textual data. These methods 
include text cleaning, tokenization, stop word removal, and lemmatization. Text input is 
converted into numerical features using TF-IDF vectorization, and the sentiment column is 
encoded for the purpose of training machine learning models. 
Accuracy measurements, classification reports, and confusion matrices are then used to train 
and assess a range of machine learning models, such as Logistic Regression, Decision Tree, K
Nearest Neighbors (KNN), Support Vector Machine (SVM), and Naive Bayes classifiers. 
Furthermore, Using RandomizedSearchCV, hyperparameter tuning is done for the SVM 
classifier to maximize model performance. Based on accuracy, the top-performing model is 
chosen, and its confusion matrix is shown to evaluate classification performance. 
Finally, the script shows how to store the TF-IDF vectorizer and the top-performing model for 
later use. In order to demonstrate the usefulness of the model in actual situations, it also has 
the ability to forecast new review data. 
