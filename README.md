# HARPY-AEROSPACE-INTERNSHIP-PROJECT-
***Recommendation System 1: Graph Neural Network (GNN)-based MovieLens Model***

Integrates graph neural networks to capture intricate relationships between movies and users in MovieLens 100k dataset for enhanced recommendation accuracy.

**Dataset:**

Utilizes the MovieLens 100k dataset.
Constructs a bipartite graph where nodes represent users and movies, and edges represent interactions (ratings).

**Features:**

Graph Structure:  Nodes represent users and movies, with edges indicating interactions (ratings).

Node Features:  Embeds user and movie features, potentially including demographic information and movie attributes.

Graph Neural Network (GNN):  Applies GNNs to learn embeddings for users and movies by aggregating information from neighboring nodes.

Recommendation: Recommends movies based on learned embeddings, capturing complex relationships and user preferences within the graph structure.





***Recommendation System 2: Enhanced MovieLens Two-Tower Model***

Implements a two-tower architecture to process user and movie features separately, combining content and collaborative filtering for personalized movie recommendations.

**Dataset:**

Uses the MovieLens 100k dataset.
Incorporates user-item interactions such as ratings and timestamps.

**Features:**

Two-Tower Architecture:   Employs two separate towers for processing user and movie features independently.

User Tower:  Processes user features like demographics and historical ratings.

Movie Tower:  Handles movie features such as genres, directors, and ratings.

Interaction:  Combines processed features to predict user preferences or ratings.

Recommendation:  Generates recommendations based on predicted ratings, blending content-based and collaborative filtering approaches.





***Recommendation System 3 : DNN MovieLens Model***

Employs deep neural networks to learn complex patterns from MovieLens 100k dataset, predicting user preferences for accurate movie recommendations.

**Dataset:**

Prepares the MovieLens 100k dataset.
Includes user ratings, movie metadata (genres, titles), and potentially demographic information.

**Features:**

Feature Representation:    Encodes user and movie features into dense vectors suitable for deep learning models.

Deep Neural Network (DNN):   Constructs a neural network architecture capable of handling input features and predicting user preferences.

Training Data:   Trains on historical user ratings to learn patterns and relationships.

Recommendation:   Uses the trained DNN to predict movie preferences for users, providing personalized recommendations based on learned patterns in the data.

These descriptions outline how each recommendation system leverages the MovieLens 100k dataset and the specific features it utilizes to generate movie recommendations.
