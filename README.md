# Project Overview
The project aims to classify hand-written digits from the MNIST dataset using Principal Component Analysis (PCA) for dimensionality reduction and a neural network for classification. The goal is to explore the impact of dimensionality reduction on model performance and gain insights into the dataset.

# Data Preparation:

We loaded the MNIST dataset, which consists of hand-written digit images.
## Original Model Training:

We defined and trained an original Convolutional Neural Network (CNN) model on the MNIST dataset. The CNN architecture includes convolutional layers, max-pooling layers, fully connected layers, and dropout for regularization.
## Principal Component Analysis (PCA):

We applied Principal Component Analysis (PCA) to the image data to perform dimensionality reduction.
The number of principal components to retain was defined as a parameter.
## PCA Model Training:

We defined and trained a new neural network model using PCA-transformed features as input. This model is designed to evaluate the impact of dimensionality reduction on model performance.
The PCA-based model includes layers for feature input, dense layers, and dropout for regularization.
## Evaluation:

We evaluated both the original CNN model and the PCA-based model on the test dataset to assess their classification accuracy.
We computed and visualized confusion matrices to understand the models' performance.
## Visualization of Principal Components:

We visualized the first few principal components obtained from PCA as images to gain insights into the dominant patterns or features captured by PCA.
Choosing the Number of Principal Components:

We explored the cumulative explained variance to help decide the optimal number of principal components to retain for dimensionality reduction.

# Conclusion
In this project, we embarked on a journey to explore the powerful combination of Principal Component Analysis (PCA) and neural networks for MNIST digit classification. Our key findings and accomplishments are as follows:

Dimensionality Reduction Success: We demonstrated that PCA, a dimensionality reduction technique, can effectively reduce the number of features while preserving essential information for classification tasks.

Model Performance: Our original Convolutional Neural Network (CNN) model, trained on the full dataset, exhibited robust accuracy, serving as a benchmark for comparison.

PCA-Based Model: The PCA-based model, trained on PCA-transformed features, highlighted the significance of dimensionality reduction. Despite reduced dimensionality, it achieved competitive accuracy.

Visual Insights: Visualizing the principal components enabled us to gain valuable insights into the dominant patterns captured by PCA, enhancing our understanding of feature importance.

Optimal PCA Components: Through an analysis of cumulative explained variance, we determined the optimal number of principal components for dimensionality reduction, striking a balance between dimensionality reduction and model performance.

