# data-cleaning 1
## IRIS Dataset Clustering Project

### Project Overview
This project demonstrates an unsupervised learning approach to cluster the famous IRIS dataset using the K-Means algorithm. The IRIS dataset contains measurements of 150 iris flowers from three different species (Setosa, Versicolor, and Virginica), with four features each (sepal length, sepal width, petal length, and petal width).

### Key Steps in the Project

1. **Data Loading and Preparation**
   - The dataset is loaded from a CSV file
   - Columns are renamed for clarity (SL, SW, PL, PW, CLASS)

2. **Unsupervised Learning Setup**
   - Input features are separated from the class labels
   - K-Means clustering is applied with k=3 (to match the three known species)

3. **Visualization**
   - A scatter plot shows the clustering results using sepal length vs petal length
   - Different colors represent different clusters

4. **Cluster Analysis**
   - Cluster centroids are examined
   - The visualization shows how well the algorithm separates the flowers based on their measurements

### Technical Details

- **Libraries Used**:
  - pandas, numpy for data manipulation
  - matplotlib, seaborn for visualization
  - sklearn for K-Means implementation

- **Key Findings**:
  - The clustering algorithm successfully groups similar iris flowers together
  - The visualization shows distinct clusters corresponding roughly to the different species
  - Cluster centroids provide insight into the average measurements for each group

### Additional Demonstration

The notebook also includes a demonstration of clustering on a randomly generated dataset using scikit-learn's `make_blobs` function, showing the versatility of the K-Means approach.

This project serves as a good example of how unsupervised learning can identify patterns and groupings in data without prior knowledge of the categories.
