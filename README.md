# Identifying Cellular Niches in Spatial Transcriptomics: An Investigation into the Capabilities of Large Language Models

An image processing pipeline leveraging Vision Transformers (ViT) to extract feature embeddings from high-resolution tissue slide images. This project facilitates spatial clustering, dimensionality reduction, and visualization for downstream analysis, providing meaningful insights in biomedical imaging.

## Features
- **Data Preprocessing**:
  - Scales and crops spot coordinates to prepare structured inputs.
- **Feature Extraction**:
  - Utilizes pretrained Vision Transformers to generate feature embeddings.
- **Clustering**:
  - Applies unsupervised K-Means clustering and PCA to uncover spatial patterns.
- **Visualization**:
  - Visualizes clustering results and embeddings in 2D space for interpretability.

## Use Cases
- Biomedical image analysis.
- Spatial pattern discovery in tissue slides.
- Unsupervised learning for high-resolution image data.

## Technologies
- Vision Transformers (ViT)
- PyTorch
- umap
- scikit-learn (K-Means, PCA)
- Matplotlib for visualization

## How to Use
1. Preprocess data using the provided scripts.
2. Extract embeddings with Vision Transformers.
3. Perform clustering using K-Means and dimensionality reduction via PCA.
4. Visualize results in 2D space for meaningful insights.
