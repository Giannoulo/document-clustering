# Document Clustering - Giannoulopoulos George
### Write a program which will parse, analyse and classify the items of the dataset into N (e.g 10) groups based on their text content

In order to use clustering on the documents the features need to be extracted. The algorithm to do that is the TF-IDF Vectorizer. TfidfVectorizer uses a in-memory vocabulary (a python dict) to map the most frequent words to features indices and hence compute a word occurrence frequency (sparse) matrix. The word frequencies are then reweighted using the Inverse Document Frequency (IDF) vector collected feature-wise over the documents. The clustering algorithm to be used is K-means.
