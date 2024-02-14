An implementation of naive bayes algorithm on toxic comment classification
Dataset is taken from IMDB(which is a movie reviews dataset) and it needs preprocessing steps
In the implementation preprocessing has been carried out(to clear double spaces, punctuations etc.,)
Vectorizer is used to create vectors of the words in the given dataset.
Given data is divided into training(to train the model), validation(evaluate the model -to know whether model has a chance to overfit or underfit) and testing( to know results on unseen data).
ROC is also plotted to know how model works on the data- it has given a value greater 0.5. So, we can say that our model works better without any underfit.

