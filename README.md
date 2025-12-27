# Spam-Email-Classifier
A machine  learning model that can automatically flag emails as "Spam" (junk) or "Ham" (legitimate).

Name: Preetam Priyadarshan Patra
Roll No.:125CR0004

I have choosen Multinomial Naive Bayes Algorithm for my model; Multinomial is designed for counts and frequencies as like TF-IDF. It checks frequency of words and likelihood of words (is the word used in Spam or Ham); Naive just assumes every word indepent to each other i helps the machine to judge a word by score given to it by TF-IDF; Bayes increases the probability of possibility (it increases the possibility of Spam=True or False by relating other words in a single array. This Algorithm is faster and can combinely work well with TF-IDF Vectorizer.

For Spam=True; F1-score=0.93
and for Spam=False; F1-score=0.99

Learning Sources:
CodewithHarry Data Science Course
YouTube: Krish Naik and CodewithHarry
Pandas User Guide: To understand DataFramming
Scikit-learn official Documentation: To understand MultinomialNB and TfidfVectorizer
Generative AI: Gemini
