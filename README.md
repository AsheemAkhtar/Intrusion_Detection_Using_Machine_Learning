Overview

This project implements an Intrusion Detection System (IDS) using the UNSW-NB15 dataset. The model leverages a Transformer-based architecture to classify network traffic as malicious or benign. The dataset is preprocessed to handle noise, scale numerical features, and balance the class distribution. The project utilizes TensorFlow and SMOTE (Synthetic Minority Oversampling Technique) for training a robust and accurate classifier.

Dataset

The UNSW-NB15 dataset is an academic dataset designed for intrusion detection tasks. It contains network traffic data labeled with attack categories and benign traffic. The dataset was preprocessed to:

Handle missing values and duplicates.

Scale numerical features using Min-Max Scaling.

Balance the class distribution using SMOTE.

Retain relevant features based on correlation with the target label.

Dataset Link: UNSW-NB15 Dataset on Kaggle

Features

Transformer-based Model: Implements a Transformer block to capture relationships between input features.

Feature Engineering: Removes irrelevant or low-correlation features.

Class Balancing: Uses SMOTE to address class imbalance in the dataset.

Visualization: Generates correlation heatmaps to understand feature relationships.
