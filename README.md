# Cluster Analysis of Gene Expression

## Project Overview

This project focuses on clustering gene expression data to uncover patterns and relationships between different gene groups. Gene expression data provides valuable insights into biological functions and disease mechanisms, and clustering helps in identifying similar expression profiles. 

By applying clustering techniques, we aim to classify genes with similar behavior, which can be useful for understanding genetic pathways, identifying biomarkers, and aiding in disease diagnosis.

## Methodology

The project follows these key steps:

1. **Data Preprocessing**  
   - Load gene expression dataset  
   - Handle missing values and normalize data  

2. **Clustering Techniques**  
   - **K-Means Clustering**: Used to segment gene expressions into different clusters based on similarity  
   - **Hierarchical Clustering**: Employed for visualizing the cluster hierarchy using dendrograms  
   - **Principal Component Analysis (PCA)**: Used to reduce dimensionality and improve clustering efficiency  

3. **Visualization**  
   - Scatter plots and cluster heatmaps to illustrate clustering patterns  
   - Dendrograms for hierarchical relationships  

## Results and Findings

- The clustering results revealed distinct gene expression groups, highlighting patterns in biological data.
- K-Means clustering successfully grouped genes based on expression similarities.
- Hierarchical clustering provided an intuitive way to visualize relationships between different gene clusters.
- PCA helped in visualizing high-dimensional gene data in a reduced 2D/3D space, making clustering more interpretable.

These findings contribute to better understanding of gene behaviors and can be used for further biological research.

## Dependencies

The following Python packages are required to run this project:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`


