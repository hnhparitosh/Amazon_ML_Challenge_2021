# Amazon_ML_Challenge_2021

Solution for Amazon ML Challenge 2021  
Team Name - CRP  
Team members: [Paritosh Dahiya](https://github.com/hnhparitosh), [Rishaab Kalra](https://github.com/PeaPals) and [Chaitanya Gupta](https://github.com/Chaitanya31612).  
* Did the basic data cleaning - lower case, replacing symbols with spaces, deleted stopwords from text.  
* Replaced NaNs with empty string ''.  
* Concatenated all the strings together.  
* Created SKlearn pipeline using CountVectorizer, tfifdTransformer.
* Tried multiple sklearn classifiers and XgBoost too, but best results were given with LinearSVC classifier.
* Trained on 50,000 samples.
* Obtained 55.47958 accuracy on test set.
* Achieved 141st rank on the leaderboard out of 3290 teams (518 teams made submissions).
