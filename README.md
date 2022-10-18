# NLP-project_Tweet_dataset_
Modeling:
Vectorizng and fiting the data: vectorizer : it will do all three steps at once. Under the hood, it computes the word counts, IDF values, and TF-IDF scores all using the same data set transformer: it will systematically compute word counts using CountVectorizer and then compute the Inverse Document Frequency values and only then compute the TFIDF scores.
