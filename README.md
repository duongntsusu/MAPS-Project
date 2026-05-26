<img width="505" height="337" alt="voronoi" src="https://github.com/user-attachments/assets/a3650951-8576-43d7-b875-71c3ecaf9a47" />

This project explores Machine Learning and data visualization using the Yelp Academic Dataset. The application predicts restaurant ratings based on user preferences and visualizes restaurant clusters across Berkeley using a Voronoi diagram. The map divides Berkeley into regions, where each region is shaded according to the predicted rating of the nearest restaurant — yellow represents highly rated restaurants (5 stars) while blue represents lower-rated restaurants (1 star). Each restaurant is displayed as a colored point on the map, with colors corresponding to geographic clusters discovered through machine learning.

This project also introduces introductory machine learning techniques, including:
1. Supervised Learning: The system predicts how a user might rate a restaurant by analyzing restaurants they have already reviewed. Using linear regression, the project models relationships between restaurant features and user ratings.
2. Unsupervised Learning: The project uses the k-means clustering algorithm to group restaurants by geographic proximity. Cluster centroids are repeatedly updated until stable restaurant regions emerge.

Project Structure
abstractions.py — Data abstractions used throughout the project
recommend.py — Machine learning algorithms and recommendation logic
utils.py — Utility functions for data processing
ucb.py — Helper and debugging utilities
data/ — Yelp users, restaurants, and reviews dataset
tests/ — Automated test suite
visualize/ — Visualization tools for rendering the final map
