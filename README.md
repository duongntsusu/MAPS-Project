<p align="center">
  <img  width="505" height="337" alt="voronoi" src="https://github.com/user-attachments/assets/a3650951-8576-43d7-b875-71c3ecaf9a47" />
</p>

This project explores Machine Learning and data visualization using the Yelp Academic Dataset. The application predicts restaurant ratings based on user preferences and visualizes restaurant clusters across Berkeley using a Voronoi diagram. The map divides Berkeley into regions, where each region is shaded according to the predicted rating of the nearest restaurant — yellow represents highly rated restaurants (5 stars) while blue represents lower-rated restaurants (1 star). Each restaurant is displayed as a colored point on the map, with colors corresponding to geographic clusters discovered through machine learning.

This project also introduces introductory machine learning techniques, including:
1. Supervised Learning: The system predicts how a user might rate a restaurant by analyzing restaurants they have already reviewed. Using linear regression, the project models relationships between restaurant features and user ratings.
2. Unsupervised Learning: The project uses the k-means clustering algorithm to group restaurants by geographic proximity. Cluster centroids are repeatedly updated until stable restaurant regions emerge.

Project Structure:
1. abstractions.py: Data abstractions used in the project
2. recommend.py: Machine learning algorithms and data processing
3. utils.py: Utility functions for data processing
4. ucb.py: Utility functions for miscellaneous and debugging
5. data: A directory of Yelp users, restaurants, and reviews
6. ok: The autograder
7. maps.ok: The ok configuration file
8. tests: A directory of tests used by ok
9. users: A directory of user files
10. visualize: A directory of tools for drawing the final visualization
