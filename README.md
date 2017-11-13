# Summary
Built a joke recommender that recommends jokes to users trained on the University of California, Berkeley's Jester dataset containing 1.2 million joke ratings provided by 51K users. Recommender achieved 12% higher user ratings on recommended jokes compared with random selection.

# Methodology
Data cleaning: Parsed HTML, stemmed words, and vectorized using term frequency-inverse document frequency (TF-IDF)

Feature engineering: Used singular value decomposition to identify 27 latent features and adjusted ratings for ‘highly-enjoyed’ jokes

Model selection: Examined results for Graphlab matrix factorization recommender model and item similarity recommender model

# Results
Final model item similarity recommender using pearson correlation similarity with a 12% better performance than random selection
