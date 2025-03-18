# Recommendation System Based on Amazon Reviews

This repository demonstrates how to build a recommendation system using Python, based on Amazon user reviews of products categorized by type. You can reach dataset at the foloowing linkhttps://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023 (you can choose what dataset you prefer). The approaches utilized in this project include:

## **Collaborative Filtering**
Collaborative filtering is a recommendation technique that predicts user preferences based on the behavior and preferences of similar users. 
There are two main types:
1. **User-based Collaborative Filtering**: Identifies users with similar preferences and suggests items liked by similar users.
2. **Item-based Collaborative Filtering**: Analyzes similarities between items based on user interactions and suggests items that are often rated similarly.

## **Content-Based Filtering**: 
Content-based filtering makes recommendations by analyzing item features and user preferences. It uses:
1. **Text embeddings** (such as TF-IDF, BoW, or deep learning models) to understand item descriptions.
2. **User profiles** created from past interactions to recommend similar items.

## **Sentiment Analysis**
Sentiment analysis involves using NLP techniques to determine the emotional tone of text data. It can help in:
1. Understanding user preferences by analyzing product reviews.
2. Improving recommendations by incorporating sentiment scores into the recommendation model.
3. Classifying content into positive, neutral, or negative sentiment categories.

# Project Structure
**Collaborative Filtering**
1. Loading and dataset creation
2. **EDA**: Descriptive statistics, dataset filtering and new statistics, variable distribution and measures of central tendency and dispersion.
3. **Recommendation models**: **KNN**, **SVD**, **rating matrix** generation and recommendation list creation.
4. **User segmentation** using **clustering**
5. Creation of **Top-K** items list for each user

**Content Based**
1. **Pre-processing**
2. **Processing textual attributes** (title and description) using **NLP**
3. **Text embedding**: **BoW**,** transformer-based models**

**Sentiment analysis**
1. Advanced processing of textual attributes: tokenization, sentiment label assingment
2. Embedding with BoW and transformers
3. Sentiment prediction

# Technologies and Libraries used:
- **Pandas** for data manipulation
- **NumPy** for numerical computations
- **Matplotlib** for data visualization
- **Scikit-Learn** for machine learning
- **Surprise** for recommendation models
- **NLTK** for NLP
- **SentenceTransformers** for text embedding
- **Torch** and **Transformers** for andvanced NLP

## Getting Started
To get started with this project, clone the repository and follow the instructions provided in the `README.md` file. You'll need to have Python (personally used 3.12.3) installed along with the necessary libraries.
Install the following libraries:
```
pip install pandas numpy matplotlib scikit-learn surprise nltk sentence-transformers torch transformers
```

