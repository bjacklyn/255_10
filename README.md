# 255_10

## Dimensionality Reduction

a) Image
* https://colab.research.google.com/drive/1-Dazm3uVr4tPhU3V8LbvXGN3Gat-Ld-K?usp=sharing
* todo

b) Tabular
* https://colab.research.google.com/drive/1I-VFpQZV90JRXnQceC6N1JCODtrMaVXG?usp=sharing
* todo

c) Databricks
* https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/966168089517560/3183543475391182/7572483456223704/latest.html
* https://www.youtube.com/watch?v=dSdlu24sBiA

## Commentary on techniques

### Linear vs. Non-linear:
PCA (Randomized and Incremental), Factor Analysis, and MDS are linear, whereas the others can handle non-linear relationships.

### Global vs. Local Relationships:
Isomap focuses on maintaining global structure whereas t-SNE, UMAP, and LLE focus on maintaining the local structures. Although hyperparameters, for example n_neighbors and min_distance in UMAP can be used to change how to consider what "local" means.

### Scalability vs. Computationally Expensive
Linear techniques like PCA scale better with large datasets whereas t-SNE, LLE, and Autoencoders are much more computationally expensive.

### Intended Use
t-SNE and UMAP are generally used for visualization only whereas the others can be used for feature extraction/dimensionality reduction of inputs before training models.
