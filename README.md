# Anime Recommendation System Using Collaborative Filtering
This project uses [data from MyAnimeList](https://www.kaggle.com/datasets/svanoo/myanimelist-dataset) in order to recommend users anime to watch. This can be accomplished using the following methods:
1. **Cosine Similarity (Memory-Based)**: This method predicts missing scores by assigning weights to users that are most similar to each other. These weights are effectively the Pearson correlations (R) between users. They are computed via normalized inner product between all user vectors. Bias is introduced by arbitrarily filling missing entries with the mean of each row or column.
2. **Matrix Factorization** or **Singular Value Decomposition**
3. **Deep Learning Methods**

**References**
1. [User-Based Collaborative Filtering](https://www.geeksforgeeks.org/user-based-collaborative-filtering/)
2. [Singular Value Decomposition vs. Matrix Factorization in Recommender Systems](https://www.freecodecamp.org/news/singular-value-decomposition-vs-matrix-factorization-in-recommender-systems-b1e99bc73599/)
   
