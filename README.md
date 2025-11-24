# Single-cell-ATAC-seq-Visualisation

This repository contains a demonstration of single-cell omics analysis and visualisation in Python. The final clusters represent groups of immune cells with similar gene expression profiles. In a full analysis, these clusters would be assigned cell-type identities using canonical marker genes. Here, the focus is on demonstrating the computational workflow rather than performing full cell-type annotation.

### What does this project do?
- Loading a small synthetic scATAC-seq dataset
- Preprocessing (normalisation, log-transform, select high variable genes)
- K-means clustering and check using elbow plot
- 2D and 3D UMAP plots

### Files
- **scATAC-seq_Visualisation.ipynb** — complete analysis notebook
- **elbow_plot_kmeans.png** - elbow plot to determine n_clusters  
- **umap_kmeans_clusters.png** — static 2D UMAP 
- **umap3d_interactive.html [LINK](https://rawcdn.githack.com/meghnasw/single-cell-ATAC-seq-Visualisation/refs/heads/main/umap3d_interactive.html) ** — standalone interactive visualisation.  

### Main script
- Follow the scATAC-seq_Visualisation.ipynb notebook
