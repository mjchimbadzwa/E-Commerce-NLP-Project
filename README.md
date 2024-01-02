# E-Commerce-NLP-Project
The following capstone project was part of satisfying the requirements of Simplilearn's AI master program. 
Steps includded Machine learning modelling, NLP, Sentimental analysis, neural networks, clustering, topic modelling

# Problem Statement
•	Amazon is an online shopping website that now caters to millions of people everywhere. Over 34,000 consumer reviews for Amazon brand products like Kindle, Fire TV Stick and more are provided.
•	The dataset has attributes like brand, categories, primary categories, reviews.title, reviews.text, and the sentiment. Sentiment is a categorical variable with three levels "Positive", "Negative“, and "Neutral". For a given unseen data, the sentiment needs to be predicted.
•	You are required to predict Sentiment or Satisfaction of a purchase based on multiple features and review text.

# Project Task: Part 1
Class Imbalance Problem:
1.	Perform an EDA on the dataset.
2.	a)  See what a positive, negative, and neutral review looks like
3.	
4.	b)  Check the class count for each class. It’s a class imbalance problem.
5.	
6.	Convert the reviews in Tf-Idf score.
7.	Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.

# Project Task: Part 2
Tackling Class Imbalance Problem:
1.	Oversampling or undersampling can be used to tackle the class imbalance problem.
2.	In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project.
3.	Use Tree-based classifiers like Random Forest and XGBoost.

# Project Task: Part 3
Model Selection:
1.	Apply multi-class SVM’s and neural nets.
2.	Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB.
3.	Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.

# Project Task: Part 4
Applying LSTM:
1.	Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.)
Hint: Another variation of LSTM, GRU (Gated Recurrent Units) can be tried as well.
2.	Compare the accuracy of neural nets with traditional ML based algorithms.
3.	Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral.

# Optional tasks Part 4 

Hint: Use techniques like Grid Search, Cross-Validation and Random Search
Topic Modeling:
1.	Cluster similar reviews.
Note: Some reviews may talk about the device as a gift-option. Other reviews may be about product looks and some may highlight about its battery and performance. Try naming the clusters.
2.	Perform Topic modeling
Hint: Use scikit-learn provided Latent Dirchlette Allocation (LDA) and Non-Negative Matrix Factorization (NMF).

