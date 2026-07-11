# K-Means Clustering & PCA for Topic Identification

## Overview

This project explores topic identification from academic articles using unsupervised machine learning techniques. The workflow combines web scraping, sentence embeddings, dimensionality reduction, and a custom implementation of K-Means clustering.

## Objective

To automatically identify and group articles discussing similar themes without using predefined labels.

## Methods

### Data Collection
- Scraped academic articles from Springer, Taylor & Francis, and Emerald publications.
- Loaded article content using LangChain's WebBaseLoader.

### Text Processing
- Split article text into manageable chunks using RecursiveCharacterTextSplitter.
- Generated vector embeddings using Hugging Face sentence embeddings.

### Dimensionality Reduction
- Applied Principal Component Analysis (PCA) to reduce embedding dimensions before clustering.

### Custom K-Means Implementation
- Built K-Means from scratch using:
  - Manhattan Distance
  - Random centroid initialization
  - Iterative centroid updates
  - Convergence checking

### Topic Interpretation
- Identified representative documents nearest to cluster centroids.
- Used a Pegasus Transformer model to paraphrase representative cluster content for easier interpretation.

## Technologies Used

- Python
- NumPy
- Scikit-Learn
- LangChain
- ChromaDB
- Hugging Face Transformers
- Sentence Transformers
- Matplotlib

## Key Achievement

Implemented a custom K-Means clustering algorithm using Manhattan distance and successfully grouped similar academic articles into topic clusters.

## Results

- Generated sentence embeddings from article text.
- Reduced dimensions using PCA.
- Clustered documents into multiple topic groups.
- Visualized clusters and centroids.
- Extracted representative article content from each cluster.

## Files

- `kmeans_pca.ipynb` - Complete project notebook

## Author

Faruk Muritala
