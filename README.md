# movielens-survey

Recommender Systems are divided into 3 broad categories - Content-Based, Collaborative Filtering (CF) and Hybrid Recommender Systems. **Content-based** systems attempt to find similar items based on attributes and recommends them to users based on their history of preference. 
**Collaborative Filtering**, on the other hand, relies on user and item interactions and disregards item contents. 
It attempts to find similar users based on similar interactions and recommends items accordingly. Lastly, **Hybrid recommender systems** combine the two techniques mentioned previously, i.e., it leverages both item attributes and user interactions to suggest items. Figure 1 summarizes the different types of recommender systems discussed above.
Here, we briefly survey different recommendation algorithms, and compare their effectiveness on the MovieLens-100K dataset.

### Dataset
We use MovieLens 100K dataset for our experiments. MovieLens dataset is one of the most comprehensive dataset on user preferences on movies. The dataset consists of 100,000 ratings from 943 users on 1682 movies. Every user has rated at least 20 movies. The ratings range from 1-5. The dataset also contains genre information for the movies and demographic user information. 17 genres are used to describe each movie in the dataset. 
These are Action, Adventure, Animation, Childrens, Comedy, Crime, Documentary, Drama, Fantasy, Film-Noir, Horror, Musical, Mystery, Romance, Sci-Fi, Thriller, War and Western.

### Libraries
Recommendation systems are separated into two main categories: 1) Rating Algorithms and 2) Ranking Algorithms. Rating Algorithms predict ratings for unknown movies for users and ranking algorithms generate recommendations for users. We used some open-source Python libraries such as Surprise, Spotlight and LightFM for implementing our recommendation models.
