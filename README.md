Unsupervised Learning Document Clustering Project
Project Overview
We’re going to work on an Unsupervised Learning Document Clustering Project, where we’ll apply clustering algorithms to two distinct datasets:


# 20 Newsgroups Dataset

A collection of approximately 20,000 news articles organized into categories. For this project, we will focus on the following categories:

- talk.religion.misc: Discussions and debates on religion and philosophy.

- comp.graphics: Technical content related to computer graphics, rendering, and 3D modeling.

- sci.space: Articles covering astronomy, space exploration, and scientific breakthroughs in space technology.


# People Wikipedia Dataset

Biographical articles with URIs, names, and text from Wikipedia. This dataset is ideal for analyzing textual content related to biographies and clustering the data into meaningful groups based on content similarity.

- Key Tasks
1- Data Collection & Preprocessing
For the 20 Newsgroups Dataset:

Use a filtered subset containing the three selected categories: talk.religion.misc, comp.graphics, and sci.space.

Preprocess the text by cleaning (removing headers, footers, and special characters) and tokenizing it for feature extraction.

For the People Wikipedia Dataset:

Load and clean biographical articles from the dataset to prepare them for clustering.

2- Feature Extraction
Represent text using:

TF-IDF Vectorization for capturing term importance across documents.


3- Clustering
Apply clustering techniques to group similar documents:

- K-Means Clustering for partitioning text data into predefined clusters.

- Hierarchical Clustering to discover nested document relationships.

- Gaussian Mixture Models (GMM) for soft clustering.

4- Evaluation
Evaluate clustering performance using metrics such as:

Silhouette Score: Measures how well-separated clusters are.

Purity Score: Quantifies the alignment of clusters with original categories.

5- Visualizations
Visualize clusters in lower-dimensional spaces using:

t-SNE for non-linear dimensionality reduction.

PCA to identify principal components.