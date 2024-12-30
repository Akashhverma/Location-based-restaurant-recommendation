Restaurant Recommendation System

Description

This project is a location-based restaurant recommendation system designed to offer personalized dining suggestions by combining geographic data with user preferences. Leveraging K-Means clustering and collaborative filtering techniques, it provides highly relevant recommendations with real-time visualizations on interactive maps.

Features

Location-based clustering of restaurants using K-Means (with K=5 and a Silhouette Score of 0.68).

Personalized dining suggestions using collaborative filtering.

Interactive map visualizations with Plotly and Folium.

Analysis of the Yelp dataset to extract restaurant data and insights.

Technology Stack

Programming Language: Python

Libraries:

Data Processing: Pandas, NumPy

Visualization: Plotly, Folium, Matplotlib, Seaborn

Clustering: Scikit-learn (K-Means)

Geospatial Analysis: GeoPandas

Installation

Clone this repository to your local machine:

git clone https://github.com/Akashhverma/Location-based-restaurant-recommendation.git

Navigate to the project directory:

cd Location-based-restaurant-recommendation

Install the required packages:

pip install -r requirements.txt

Download the Yelp dataset and place it in the project directory.

How It Works

Data Processing: The Yelp dataset is processed to filter restaurant data and relevant features such as location, review count, and ratings.

Clustering: Restaurants are grouped into clusters based on geographic coordinates using K-Means clustering.

Recommendation Engine: User location is mapped to a cluster, and the top-rated restaurants in that cluster are recommended using collaborative filtering.

Visualization: Recommendations and clusters are visualized on interactive maps.

Results

Achieved a Silhouette Score of 0.68 for K-Means clustering (K=5).

Enhanced recommendation accuracy by integrating collaborative filtering with geographic clustering.

Usage

Run the main script to process the data and generate recommendations:


Enter user location coordinates to receive the top 5 restaurant recommendations.

View results on an interactive map.

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
