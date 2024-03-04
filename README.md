# Research_Paper_Recommender

Research paper recommenders usually use co-citation scores to give recommendations. <br>
My code creates vectors from research paper title and abstract and uses a similarity search to give recommendations

*Features*

* Cosine similarity-based recommendations using TFIDF word vectors.
* Recommendations based on clustering
* Visualised clusters of similar papers with important topics in each cluster
* Web application developed in Flask

*Methodology*

* Combined all the preprocessed text and calculated the Term Frequency-Inverse Document Frequency (TF-IDF) vector for each research paper.
* Used the TF-IDF matrix to calculate cosine similarity between research papers.
* Used cosine similarity score to recommend similar research papers for a given research paper.
* To search and recommend research papers to users, we created a web app using Flask.
* Used Principal Component Analysis (PCA) to project down the dimensions of the TF-IDF matrix to several dimensions that will keep a .95 variance
* Apply K-Means Clustering on the new data and use these clusters to make recommendations.
* Apply Dimensionality Reduction to each feature vector using t-Distributed Stochastic Neighbour Embedding (t-SNE) to cluster similar research articles in the two-dimensional plane.
* Apply Topic Modeling on the clustered data using Latent Dirichlet Allocation (LDA) to discover keywords from each cluster.

*Screenshots*
