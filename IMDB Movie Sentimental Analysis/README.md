
# IMDB-Movie-Sentimental-Analysis

Link to dataset: http://ai.stanford.edu/~amaas/data/sentiment/

- Completed building a sentimental analysis model with 88% accuracy using Naive Bayes Classfier.

I observed that while considering bigrams and trigrams, the accuracy of the model dropped on data that had stop-words removed. Words like `not` and `but` which are classfied as stop-words can greatly affect the polarity of the sentiment of a comment or text. And that is why my best model was achieved on data that still included stop-words, but was cleaned (html tags, url links, numbers, etc all removed).
