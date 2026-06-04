# EEG-based ADHD Diagnosis Pipeline Optimization

> This repository implements and optimizes the hybrid machine learning pipeline inspired by the original paper.

## Reference Paper
* **Original Paper:** "[EEG-Based ADHD Diagnosis Using Autoencoder and Reptile Search Algorithm Integrated with Machine Learning]"
* **DOI:** [10.1177/15500594251390030]
* **Link:** [https://pubmed.ncbi.nlm.nih.gov/41160507/]

## Our Improvements
* **Original Pipeline:** Unsupervised Autoencoder -> RSA -> Classifiers
* **Our Optimized Pipeline:** **Supervised Autoencoder (Label-guided)** -> RSA -> Classifiers
* **Result:** Achieved **97.2% Accuracy** (AUC 0.99) with AdaBoost by filtering noise and capturing class-separable features.
