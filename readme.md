Netflix Movies and TV Shows Clustering
This project aims to cluster Netflix content based on attributes such as Director, Cast, Country, Genre, and Description. By leveraging machine learning techniques, the project uncovers patterns and relationships among the vast library of movies and TV shows on Netflix.

Project Overview
Data Source: Netflix dataset containing attributes like Director, Cast, Country, Listed In (Genres), and Description.
Goal: To cluster similar movies and TV shows using unsupervised learning techniques.
Key Steps
Data Preprocessing

Handled missing values.
Removed non-ASCII characters, stopwords, and punctuation.
Converted textual data to lowercase.
Performed lemmatization and tokenization.
Feature Engineering

Combined relevant textual features to create a comprehensive representation for clustering.
Clustering

Implemented K-Means and Hierarchical clustering.
Determined optimal clusters using silhouette scores and dendrograms.
Visualization

Generated word clouds to visualize the characteristics of each cluster.
Tools and Libraries
Programming Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, wordcloud
Results
The project successfully clustered Netflix movies and TV shows, providing insights into the content's similarities based on the selected attributes. The visualizations offer a clear understanding of each cluster's unique characteristics.

Future Work
Explore additional features for clustering.
Apply advanced NLP techniques for better text analysis.
Experiment with other clustering algorithms.
Acknowledgments
Thanks to Netflix for providing the dataset and to the open-source community for the powerful tools and libraries used in this project.