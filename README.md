# Summary
Built a joke recommender that recommends jokes a given user is most likely to enjoy, based on the University of California, Berkeley's Jester dataset containing 1.2 million joke ratings provided by 51K users.

# Methodology
Data cleaning: Parsed HTML, stemmed words, and vectorized using term frequency-inverse document frequency (TF-IDF)

Feature engineering: Used singular value decomposition to identify 27 latent features and adjusted ratings for ‘highly-enjoyed’ jokes

Model selection: Examined results for Graphlab matrix factorization recommender model and item similarity recommender model

# Outcome
Final model item similarity recommender using pearson correlation similarity with a 12% better performance than random selection
