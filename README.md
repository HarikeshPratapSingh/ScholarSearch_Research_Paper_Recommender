# Scholar Search

Research paper recommenders usually use co-citation scores to give recommendations. <br>
Scholar search creates vectors from the research paper title and abstract and uses a similarity search to give recommendations

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
* Apply Dimensionality Reduction to each feature vector using t-distributed Stochastic Neighbour Embedding (t-SNE) to cluster similar research articles in the two-dimensional plane.
* Apply Topic Modeling on the clustered data using Latent Dirichlet Allocation (LDA) to discover keywords from each cluster.

*Screenshots*

![img1](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/8c26bffc-6023-4b3b-b198-9ec9080869c9)

![img2](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/e08a2b59-b3ed-46e2-8844-07e287afbf18)

![img3](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/7caabfdb-1b33-471a-a33f-f60b409aa91b)

![img4](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/8ad81aed-63f8-4486-8baf-cbb0c2cf5726)

![img5](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/6c6130bc-0769-49d6-a7cf-07a009044228)

![img6](https://github.com/HarikeshPratapSingh/Research_Paper_Recommender/assets/71792788/ff148eed-5b06-4ae4-946b-adcf651a5dbb)
