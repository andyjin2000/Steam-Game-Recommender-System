# Steam-Game-Recommender-System

Steam is the largest digital distribution platform for PC gaming. It has over 7,000 games available, with over 125 million active users. This project focuses on building a game recommendation system for Steam users. That is, given a user's existing game record (i.e. which games they have played and their ratings of those games), we will develop an engine that proposes new games that the user may enjoy. We will extract data using the Steam Web API: GetOwnedGames for a sample of 5,000 users. 

This project implements 4 recommender system algorithms:
1. Popularity-based Filtering - no customization, outputs the same list of trending games for every user
2. Content-based Filtering - recommends games that have similar properties to games the user already likes
3. Collaborative Filtering - recommends games that other users whose preferences are similar to the user also like
4. Alternating Least Squares - matrix factorization via Apache Spark ML can uncover latent factors that underlie user preferences
