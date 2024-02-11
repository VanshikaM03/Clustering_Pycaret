# Clustering_Pycaret
# *Clustering Analysis Project*

This project utilizes the *PyCaret* library in Python to perform clustering analysis. Clustering is an unsupervised learning technique that groups data points together based on similarity, with the goal of discovering underlying patterns and structures within the data.

## *PyCaret*

*PyCaret* is an open-source, low-code machine learning library in Python that simplifies the machine learning workflow. It provides an easy-to-use interface for training, tuning, evaluating, and deploying machine learning models, making it suitable for both beginners and experienced data scientists.

## *Clustering Algorithm Used*

For this project, we employed three clustering algorithms available in *PyCaret*:

1. **KMeans Clustering**: A partition-based clustering algorithm that divides the dataset into 'k' distinct non-overlapping clusters.

2. **Hierarchical Clustering**: A hierarchical clustering algorithm that builds a tree of clusters by recursively merging or splitting them based on distance measures.

3. **Mean Shift Clustering**: A density-based clustering algorithm that identifies clusters as regions of high density separated by regions of low density.

## *Parameters and Preprocessing*

We experimented with various preprocessing techniques and parameters to observe their impact on clustering performance. These techniques include:

- **Normalization**: Scaling the features to a similar range, often using methods like z-score normalization.
- **Transformation**: Applying mathematical transformations to the features, such as Yeo-Johnson transformation.
- **Principal Component Analysis (PCA)**: Reducing the dimensionality of the dataset using PCA, which can help improve clustering performance.
- **Combination of Preprocessing Techniques**: We also explored combinations of normalization, transformation, and PCA to observe their combined effects on clustering.

## *Usage*

To replicate this clustering analysis, follow these steps:

1. Ensure you have Python installed on your system along with the necessary libraries (*PyCaret*, *pandas*, *matplotlib*).
2. Download the dataset and place it in the project directory.
3. Open the provided Jupyter Notebook or Python script.
4. Execute the code cells or run the script to perform clustering analysis using *PyCaret*.
5. Analyze the generated plots and evaluate the clustering performance based on the chosen parameters and preprocessing techniques.



