# Unsupervised Learning Techniques to Label Unstructured Agricultural Supply Chain Data

This repository contain the codes for the implementations of the paper "USE OF UNSUPERVISED LEARNING TECHNIQUES TO LABEL UNSTRUCTURED AGRICULTURAL SUPPLY CHAIN DATA", by ROBERTO F. SILVA, GUSTAVO M. MOSTAÇO, FERNANDO XAVIER, ANTONIO MAURO SARAIVA and CARLOS E. CUGNASCA

The main objective of this work was to demonstrate that unsupervised machine learning techniques can be successfully used to identify clusters and generate labels for a non-standardized unlabeled agricultural supply chain (SC) dataset. This would contribute to reduce interoperability problems that can be observed in real life scenarios. To the best of our knowledge, this is one of the few attempts to address this problem using unsupervised machine learning techniques. The following techniques were implemented on a dataset consisting of the fusion of 7 agricultural-related datasets: K-means, PCA-2 + K-means, PCA-3 + Kmeans, and Self Organizing Maps (SOM). Considering traditional supervised learning, supervised clustering, and unsupervised clustering metrics, we concluded that the SOM resulted in a better clustering of the data. The results and possible impacts on SCs are discussed on the paper. Future works are also cited on the paper.

For gaining access to the Google Colab notebooks, please refer to roberto.fray.silva@gmail.com

Sources:
- Dataset: refer to the paper, in which there are instructions for creating the dataset
- Source of the PCA chart implementation on the k-means and PCA+k-means notebooks: https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_digits.html
- Source of the minisom SOM implementation, map and the minisom model: https://github.com/JustGlowing/minisom
