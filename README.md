# Document Clustering
Cluster documents based on various similarity measures. The project is based on 'Bag of Words' data from [*UCI Machine Learning Repository*.](https://archive.ics.uci.edu/ml/datasets.php)

## Dataset Description:
The dataset contains two important files, **docword** and **vocab**. Depending on your choice of set of documents, you can choose any one of Enron emails, KOS Blog entries, NY Times news articles, etc. Just change the file paths accordingly. The detailed dataset description can be found at the [official UCI website.](https://archive.ics.uci.edu/ml/datasets/Bag+of+Words). For this notebook I have used *KOS blog entries* data.

## Current Work:
- Finding out *tf-idf* scores of every term in the set of documents
- Creating the Normalized Document Vectors and storing the *data matrix* 
- Finding *cosine similarity* and perform clustering using various algorithms.

## Work which can be done:
- Clustering based on different criteria like *Jaccard Index*, etc.
- Some additional clustering algorithms.

**Please suggest any improvements, and kindly 'star' the repository if you like it! Thank you!**
