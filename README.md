# Recommendations with IBM

Approach: Used IBM Watson user, article, user article interaction data to build a recommendation system for recommending articles to users. First performed EDA to explore the data.
Then used Rank-Based Recommendations to get top articles for users by rank based on article popularity.
User-User-based collaborative filtering is also used which recommends articles based on similar users and interests.
Then used another method using articles context (text) features build a context-based recommendation which recommends article based on the similar interacted article.
Finally, built the last model using Singular Value Decomposition. Using almost 300 latent features SVD yields good performance for recommending articles.
