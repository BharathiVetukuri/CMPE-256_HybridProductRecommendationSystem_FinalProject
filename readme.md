# Hybrid-Product-Recommendation-System

A scalable hybrid recommendation system that combines Singular Value Decomposition (SVD), TF-IDF and Random Forest to provide personalized product recommendations.

# Overview

This project implements a hybrid recommendation system combining three approaches:
- Collaborative Filtering using SVD (Singular Value Decomposition)
- Content-Based Filtering using TF-IDF
- Hybrid approach using Random Forest to combine both methods
![image](https://github.com/user-attachments/assets/a3012dee-2b11-413b-9d61-13d2905c2228)

# Artifacts:

### Youtube Links:

**Full Demo Youtube Link:** https://youtu.be/pKpgschLBFc 

**Application Run with Gradio UI Demo Youtube Link:** https://youtu.be/35OBaW7t4B4 

### Colab Links:

**Hybrid Product Recommendation System:** https://colab.research.google.com/drive/1gkSlkkvmVvr1uwGFIyoBisSh5ZaJjNia?usp=sharing 

**Product Recommendation User Interface:** https://colab.research.google.com/drive/17CENL-xktRCrPAgYPxFI3Evx8ztOBNPF?usp=sharing 

**Model Deployment:** https://colab.research.google.com/drive/17CENL-xktRCrPAgYPxFI3Evx8ztOBNPF?usp=sharing

### Dataset:

**Products.csv** :  https://github.com/BharathiVetukuri/CMPE-256_HybridProductRecommendationSystem_FinalProject/blob/main/Products.csv 

(Source: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) 

### Models:

**Content-Based Filtering:** https://github.com/BharathiVetukuri/CMPE-256_HybridProductRecommendationSystem_FinalProject/blob/main/content_based_scaler.pkl.zip , https://github.com/BharathiVetukuri/CMPE-256_HybridProductRecommendationSystem_FinalProject/blob/main/content_based_tfidf.pkl.zip 

Content-Based, Collaborative-Based Filtering and Hybrid Models are deployed to the Model Bit Servers. The models can be even downloaded after Colab execution.

# Features

**Collaborative Filtering (SVD)**
- Matrix factorization for user-item interactions
- Handles sparse rating matrices efficiently
- Captures latent features from user behavior

**Content-Based Filtering (TF-IDF)**
- Text analysis of product descriptions
- Feature extraction from product attributes
- Cosine similarity for item matching

**Hybrid Approach (Random Forest)**
- Combines predictions from both models
- Optimizes weights dynamically
- Handles cold-start problems effectively

# Steps to Run:

* Download Products.csv
* Based on the functionality, choose the .ipynb file to execute.
* Upload the dataset(products.csv) to the colab file and run the cells of the Colab.
* Sample Input: New Customer ID: 123456, Existing Customer ID: 0c9ff9d8ed9b9bdd825487b3a66e05f5  
* Expected Output: Top 5 recommended products.

# Results:

<img width="450" alt="image" src="https://github.com/user-attachments/assets/40df5561-bd5e-4c46-b38d-d093fa96fbd0">

![image](https://github.com/user-attachments/assets/bcd1c74e-9679-4bdc-bce6-b27234d2294e)

