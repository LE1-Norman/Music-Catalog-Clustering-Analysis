# Music-Catalog-Clustering-Analysis
ML project for music catalog segmentation using clustering methods

This project aims to identify the dependencies between musical features of tracks in order to group all tracks into different categories. The goal is to use clustering techniques to identify major musical subgroups that can be used in a recommendation system.

Data source: https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

Size: 114000 lines, 21 features

This project covers all stages of the machine learning process, from data collection and preprocessing to model training with optimal parameters. We used several methods in our work, including K-means, DBSCAN, and hierarchical clustering, to achieve the best results.

Through our analysis, we identified five large clusters that best describe musical diversity. These clusters were selected based on their ability to fully capture the diversity of the data.
After identifying these clusters, we evaluated the performance of several models using various metrics. We compared the results of these models to determine which one was most effective at classifying new data into the appropriate cluster.

Results:

Модель | Silhouette Score | Calinski-Harabasz Score | Davies-Bouldin Score |
K-means| 0.394            | 135542.5                |   0.919              |
DBSCAN | -0.127           | 1005.711                |   1.071              |
Hierarchical | 0.482      | 123610.785              |   0.792              |
