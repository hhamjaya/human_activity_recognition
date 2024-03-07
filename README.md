# Machine Learning Lab 3

## Project Overview

In this project, we will apply unsupervised learning techniques to cluster human activity data collected from smartphones. The dataset includes sensor data (accelerometer and gyroscope readings) from 30 volunteers performing six different activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING). Using **K-Means** and **DBSCAN**, we will explore how clustering can reveal underlying patterns in the data. We will also experiment with dimensionality reduction techniques to improve computational efficiency and clustering results.

## Dataset

The dataset used in this project was collected from **30 volunteers** aged between 19-48 years. Each volunteer performed six activities while wearing a smartphone (Samsung Galaxy S II) on their waist. The smartphone captured data at a rate of 50Hz using its embedded accelerometer and gyroscope. The dataset has been preprocessed, and the sensor data is divided into fixed-width sliding windows (2.56 seconds with 50% overlap), which are then used for feature extraction.

### Dataset Details:

- **Activities**: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
- **Features**: 3-axial linear acceleration and 3-axial angular velocity (accelerometer and gyroscope readings).
- **Data Processing**: Data was filtered using a Butterworth low-pass filter, separating body acceleration and gravity.

The dataset is divided into a training set (70% of the volunteers) and a test set (30% of the volunteers). You can access the dataset [here](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

## Project Tasks

### Task 1: Clustering with K-Means and DBSCAN

- **K-Means Clustering**:
  - Perform clustering using the K-Means algorithm.
  - Explore how to choose the optimal number of clusters for K-Means.
  - Compare the number of clusters used in K-Means with DBSCAN.

- **DBSCAN Clustering**:
  - Perform clustering using DBSCAN (Density-Based Spatial Clustering of Applications with Noise).
  - Identify the optimal parameters for DBSCAN (e.g., epsilon and minimum samples).
  - Compare the clustering results with K-Means.

Key questions to address:
- How do you choose the number of clusters in K-Means?
- Are the number of clusters the same for DBSCAN? Why or why not?
- How do you find the optimal parameters for both K-Means and DBSCAN?

### Task 2: Dimensionality Reduction

- **Dimensionality Reduction**:
  - Choose a dimensionality reduction technique (e.g., PCA, t-SNE, or UMAP) to reduce the feature space.
  - Analyze the impact of dimensionality reduction on both the computational efficiency and the clustering output.

- Key questions to address:
  - What dimensionality reduction technique did you choose and why?
  - How does dimensionality reduction affect the performance of the clustering models?
  - Compare the clustering outcomes with and without dimensionality reduction.

### Task 3: Visualizing the Clusters

- Visualize the clustering results using appropriate techniques (e.g., scatter plots, pair plots).
- If dimensionality reduction was applied, visualize the data in 2D or 3D after reduction.

Key questions to address:
- How does dimensionality reduction affect the visual representation of the clusters?
- What insights can you gain from the visualized clusters?

### Task 4: Scientific Report

Write a report that includes the following sections:

1. **Introduction**:
   - What problem are you solving? Why is clustering important in the context of human activity recognition?

2. **Data Processing**:
   - What steps did you take to process the raw sensor data (e.g., noise filtering, windowing)?
   - How did you prepare the data for clustering (e.g., feature extraction, normalization)?

3. **Modeling**:
   - How did you apply K-Means and DBSCAN for clustering?
   - What parameters did you choose for each algorithm and how did you determine them?
   - What impact did dimensionality reduction have on the clustering process?
   - How did you evaluate the clustering results?

4. **Conclusion**:
   - How do you interpret the identified clusters? What do they represent in terms of the human activities?
   - What were the key challenges and bottlenecks encountered during the project?
   - How did you overcome these challenges? 


## Overall Feedback:
Overall well done implementation of the project.