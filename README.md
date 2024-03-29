# Clustering Assignment 

## Introduction
This repository contains the code and documentation for a clustering assignment using PyCaret. The assignment involves implementing three clustering algorithms (K-means, MeanShift, and Hierarchical Clustering) and plotting 3D graphs for visualization.

## Dataset
The dataset used for this assignment is Credit-Card-Dataset. This dataset contains The Credit Card Dataset typically contains information about credit card transactions, including various attributes such as transaction amount, time of transaction, whether the transaction is fraudulent or not, and potentially additional features related to the transaction.
Before using the dataset, it's recommended to review the dataset documentation or metadata to understand the attributes and any data preprocessing steps that may be required. Additionally, data cleaning and feature engineering may be necessary to prepare the dataset for modeling tasks.

## Setup
1. Clone this repository to your local machine.
2. Ensure you have Python 3 installed on your machine.
3. Install the required libraries by running:pycaret

## Code Structure
- `clustering_assignment.ipynb`: Jupyter Notebook containing the code for the clustering assignment.
- `data/`: Credit-Card-Dataset.
- `plots/`: images of 3d plots.

## Implementation
### 1. Data Preprocessing
- Load the dataset.
- Perform any necessary data preprocessing steps such as handling missing values, encoding categorical variables, etc.

### 2. Clustering Algorithms
- Implement K-means clustering using PyCaret.
- Implement MeanShift clustering using PyCaret.
- Implement Hierarchical Clustering using PyCaret.

### 3. Visualization
- Plot 3D graphs to visualize the clusters generated by each algorithm.
- Save the plots in the `plots/` directory.

## Running the Code
1. Open `clustering_assignment.ipynb` in Jupyter Notebook.
2. Execute each cell in the notebook to run the code.
3. The notebook will generate plots and display the results of each clustering algorithm.

## Results
- K-means clustering: [Silhouette=0.5568]
- MeanShift clustering: [Silhouette=0.6358]
- Hierarchical Clustering: [Silhouette=0.5225]

## Conclusion
In this assignment, we implemented three clustering algorithms (K-means, MeanShift, Hierarchical Clustering) using PyCaret and visualized the clusters using 3D graphs. Each algorithm generated distinct clusters, and further analysis can be done to interpret and evaluate the results.




