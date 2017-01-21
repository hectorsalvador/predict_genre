# predict_genre
Uses the [Brown Corpus](http://www.nltk.org/book/ch02.html) data from the nltk library to train a model that can predict the genre of a text. The classifier uses linear interpolation that combines 1-gram, 2-gram, and 3-gram models.

F1-score: 0.4039
Lambdas: 0, 0.9, 0.1 (for 1-gram, 2-gram, and 3-grams respectively)