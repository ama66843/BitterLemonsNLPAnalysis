# nlpbitterlemonsexplor
uses spaCy to see whether syntactic information can improve semantic prediction

created by Austin Apt December 2019
a lot of the code inspiration is taken from NLP Tutorial 8 - Sentiment Classification using SpaCy for IMDB and Amazon Review Dataset
git: laxmimerit 
https://github.com/laxmimerit/NLP-Tutorial-8---Sentiment-Classification-using-SpaCy-for-IMDB-and-Amazon-Review-Dataset

This was created for a natural language processing course I took in Fall 2019. There are various functions such as text cleaning/
pre-processing, data I/O and prediction models. The code works on the Bitterlemons dataset which contains 512 
news articles and essays written by Israeli and Palestinian authors during the early 2000's. There are an equal number of each in 
the data. 

The program compares the results of document classification given only the text versus the text with syntactic information
such as a word's part of speech, or dependency. Although not entirely correct due to there being words with multiple POS tags
in the 2nd model, it did perform better on classifying documents given this syntactic information.

The idea was that seeing named entities such as Ariel Sharon or Arafat paired with negative adjectives or verbs would
improve information as to who the author of the document is. 
