# Airbnb Analysis and Clustering in Athens
This repository contains code and analysis for clustering Airbnb listings in Athens, Greece, based on various features such as room types, prices, location, and other factors.
The project aims to provide insights into the distribution of different types of listings, analyze booking patterns, and identify clusters of listings with similar characteristics.

Dataset:
The dataset used in this project is a collection of Airbnb listings in Athens. 

Data Preparation:
The dataset is preprocessed and cleaned to prepare it for analysis and clustering.
It includes information such as:

realSum: Total number of bookings
room_type: Type of room (e.g., entire home/apartment, private room, shared room)
room_shared: Number of shared rooms
room_private: Number of private rooms
host_is_superhost: Indicator of whether the host is a superhost
cleanliness_rating: Rating for cleanliness
guest_satisfaction_overall: Overall guest satisfaction rating
dist: Distance from the city center
metro_dist: Distance from the nearest metro station
attr_index: Index representing proximity to attractions
rest_index: Index representing proximity to restaurants

Average Price for Types of Listings: 
The average price for each type of listing is calculated to understand pricing trends.

Clustering:
K-means clustering is applied to the dataset to group listings into clusters based on various features. Silhouette scores are used to evaluate the quality of clustering.

Dimensionality Reduction:
T-distributed Stochastic Neighbor Embedding (t-SNE) is utilized to visualize the dataset in 2D and 3D space, providing insights into the distribution and separation of listings.
Attraction Per Clusters: Attractions in Athens are mapped to the clusters to analyze their distribution among different clusters of Airbnb listings.

Distribution Visualization:
Folium maps are generated to visually inspect the distribution of Airbnb listings across different areas of Athens.

Stavros Doundoulakis & Spiridon Spiros --> https://github.com/SpyridonSpyros
