# Face_Representation_And_Similarity
Developed a lightweight pipeline using PCA and t-SNE for dimensionality reduction and visualization of face data. Implemented KMeans, Agglomerative, and DBSCAN clustering, evaluated with ARI/NMI metrics. Built a cosine similarity–based retrieval system with precision@k evaluation, enabling face verification without deep learning.

## Workflow
Load and preprocess the LFW dataset

Exploratory Data Analysis (EDA) with sample images and class distributions

PCA (Eigenfaces) for feature extraction & dimensionality reduction

t-SNE visualization for 2D embedding of identities

Clustering with KMeans, Agglomerative, and DBSCAN + evaluation using ARI & NMI

Similarity checking & retrieval using cosine similarity on PCA features

Precision@k evaluation for retrieval performance


## Output

Top Eigenfaces visualization

t-SNE scatterplot of identities

Clustering performance metrics (ARI, NMI)

Retrieval: Query image + Top-k neighbors

## Next Steps

Use pre-trained face embeddings for stronger baselines

Explore metric learning approaches (PCA + LDA, pairwise metric learning)

Analyze demographic balance & cluster purity

