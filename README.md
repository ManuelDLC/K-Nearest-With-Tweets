# K-Nearest-With-Tweets
Implements K-Means clustering from scratch in Python to group 
health-related tweets by topic similarity. Uses Jaccard Distance 
as the similarity metric (rather than Euclidean) since tweets are 
represented as word sets, not numeric vectors. Includes a full 
preprocessing pipeline that strips URLs, @mentions, and hashtags 
before tokenizing.
