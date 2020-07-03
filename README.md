# TextAnalysis-SpamClassifier  
The key objectives of this project is to classify spam/ham messages solely based on text analysis. If some words occur only in spam messages but not in ham messages, then these words are more possibly the 'symbols' of spam messages. The result of classification for each messages is the sum of individual TF-IDF for each word.    

**The formula for TF-IDF calculation:**

TF-IDF = Term Frequency (frequency of words/# of words in the message) * IDF (log(total number of messages/number of messages containing the word))
