# Dimensionality Reduction with Databricks

This project demonstrates various dimensionality reduction techniques applied to datasets using the Databricks platform. It includes visualizations of results and a comparative analysis of techniques to understand their effectiveness in reducing dimensions while preserving important features of the data.

## Overview

Dimensionality reduction is a key aspect of machine learning that simplifies datasets by reducing the number of features while retaining as much information as possible. This project leverages the Databricks environment to apply and analyze the following dimensionality reduction techniques:

1. Principal Component Analysis (PCA)
2. t-Distributed Stochastic Neighbor Embedding (t-SNE)
3. Uniform Manifold Approximation and Projection (UMAP)
4. Linear Discriminant Analysis (LDA)

## Techniques Demonstrated

### 1. Principal Component Analysis (PCA)
PCA reduces the dimensions of the dataset by projecting it onto the directions of maximum variance.

- **Input**: Iris dataset.
- **Output**: 2D scatterplot showing clusters by species.

### 2. t-Distributed Stochastic Neighbor Embedding (t-SNE)
t-SNE is a nonlinear dimensionality reduction technique for visualizing high-dimensional data in low-dimensional space.

- **Input**: Iris dataset.
- **Output**: 2D scatterplot showing better-separated clusters.

### 3. Uniform Manifold Approximation and Projection (UMAP)
UMAP is a non-linear technique used for both dimensionality reduction and visualization.

- **Input**: Iris dataset.
- **Output**: Interactive 2D scatterplot for cluster visualization.

### 4. Linear Discriminant Analysis (LDA)
LDA reduces dimensions by maximizing the separability between categories.

- **Input**: Iris dataset.
- **Output**: 2D scatterplot showing separated clusters by species.

## Dataset

- **Name**: Iris Dataset.
- **Source**: Preloaded dataset from `sklearn.datasets`.
- **Description**: A dataset with 150 records of iris flowers, categorized into three species based on four features: sepal length, sepal width, petal length, and petal width.

## Environment

- **Platform**: Databricks
- **Language**: Python
- **Libraries Used**:
  - `pyspark` for data processing
  - `sklearn` for dataset and dimensionality reduction techniques
  - `matplotlib` and `plotly` for visualization
  - `umap-learn` for UMAP
  - `openTSNE` for t-SNE

## How to Run the Notebook

1. **Upload the Notebook**: Clone the repository and upload the notebook to your Databricks workspace.
2. **Attach to Cluster**: Attach the notebook to a running cluster in Databricks.
3. **Execute the Cells**: Run the cells sequentially to:
   - Load and process the Iris dataset.
   - Apply dimensionality reduction techniques.
   - Visualize results.

