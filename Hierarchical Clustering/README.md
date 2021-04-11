### Hierarchical Clustering using MNIST Database

Based on Hierarchical clustering, I have used the MNIST dataset which is a dataset for handwritten images.
1. First, I have imported the libraries of python and scikit-learn.
2. After that, I have imported the dataset of MNIST. 
3. Then, I have carried out embedding in 2D using spectral embedding. I have carried out the merges using different linkage criteria: ward linkage, average linkage, complete linkage and single linkage.
4. Ward linkage function specifying the distance between two clusters is computed as the increase in the "error sum of squares" (ESS) after fusing two clusters into a single cluster.
5. Average-linkage clustering is a compromise between the sensitivity of complete-linkage clustering to outliers and the tendency of single-linkage clustering to form long chains that do not correspond to the intuitive notion of clusters as compact, spherical objects.
6. In complete-linkage hierarchical clustering, I have merged in each step the two clusters whose merger has the smallest diameter (or: the two clusters with the smallest maximum pairwise distance).
7. In single-linkage hierarchical clustering, I have merged in each step the two clusters whose two closest members have the smallest distance (or: the two clusters with the smallest minimum pairwise distance).
8. Then, I have plotted the dendrogram. To plot the dendogram, I carried out visualization of number of clusters by assuming distance between points. 
9. The model is computationally intensive so I have worked on a dataset of 1000 points instead of 60000 points.




