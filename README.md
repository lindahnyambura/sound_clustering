# Sound Clustering with Dimensionality Reduction

This repository contains a Jupyter notebook for unsupervised clustering of a large set of sound recordings using K-Means and DBSCAN. 
The project explores how dimensionality reduction (PCA and t-SNE) affects clustering quality and interpretability.


### Contents
`sound_clustering.ipynb`: Main notebook containing all steps from feature extraction to clustering and evaluation.

### Objectives

- Extract meaningful features (Mel Spectrograms) from raw sound data.

- Visualize high-dimensional audio features before and after dimensionality reduction.

- Compare PCA and t-SNE for visual separability.

- Apply and evaluate K-Means and DBSCAN clustering algorithms.

- Interpret clustering performance using inertia, silhouette score, and Davies-Bouldin index


### Dataset
The dataset used for this project consists of 3,035 unlabeled sound recordings.
You can download the dataset from the following link:

[Download Sound Dataset](https://www.google.com/url?q=https://drive.google.com/file/d/1bme1IuScdIWjzFkYPOcWzFOgD50MS_zR/view?usp%3Dsharing&sa=D&source=editors&ust=1751524126539941&usg=AOvVaw3IwV8exw0GT8xzvjrxZe9a)


### Results Summary

- PCA preserved global structure for metric-based clustering; t-SNE emphasized visual separation.

- DBSCAN on PCA produced the best results after tuning eps, with high silhouette and low Davies-Bouldin scores.

- K-Means was simpler to apply but performed less accurately on irregular cluster shapes.

- Dimensionality reduction was critical for both performance and interpretability.

