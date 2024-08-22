# Biomedical Image Clustering

This project aims to use unsupervised clustering algorithms like K-means, Agglomerative, Gaussian Mixture, Spectral and K-Medoids (PAM) to cluster blood smear images for the detection of malaria.

### **The workflow includes:**
1. **Loading of the images**
2. **Preprocessing:**
   + Resizing
   + Sobel filtering
   + Watershed Segmentation
4. **Feature Extraction:** using the VGG16 deep learning model with its softmax layer removed.
5. **Feature Selection:** Variance Threshold method
6. **Clustering:**
   + K-means
   + Agglomerative
   + Gaussian Mixture Model
   + Spectral
   + K-Medoids (Partitioning Around Medoids)
7. **Evaluation Metrics:**
   + Homogeneity
   + Completeness
   + V-measure
   + Adjusted Rand Index Score
   + Adjusted Mutual Information
   + Sihouette Score
   + Calinksi Harabasz Index
   + Davies-Bouldin Score
    
