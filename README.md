# Twitter Sentiment Analysis
Detects the hate speech in tweet and trending Hashtags.
<br>
Tools \& technologies used: Natural Language Processing, SciKit-Learn, Seaborne, MatplotLib
<br>
Created Bag of Words and Implemented Logistic Regression, Naive Bayes and Random Forest Classifier and SVM.
<br>
<br>
<br>
<br>
<br>
## CONCLUSION
Top Three Models: Upon evaluating all the models we can conclude the following details i.e.

Accuracy: As far as the accuracy of the model is SVM performs better than Logistic Regression which in turn performs better than RandomForestClassifier.

F1-score: The F1 Scores for class 0 ,class 1 and class 2 are : (a) For class 0: RandomForestClassifier(F1_score = 0.66) < Logistic Regression (F1_score = 0.70) < SVM (F1_score =0.71) (b) For class 1: RandomForestClassifier (F1_score = 0.67) < SVM (F1_score = 0.72) = Logistic Regression (F1_score = 0.72) (c) For class 2: RandomForestClassifier (F1_score = 0.90) < SVM (F1_score = 0.92) = Logistic Regression (F1_score = 0.92)

We, therefore, conclude that the Support Vector Machine is the best model for the above-given dataset. Since our dataset does not have any assumptions and Logistic Regression is a simple model, therefore the concept holds true for the above-mentioned dataset i.e. the simple model will have a better performance.
