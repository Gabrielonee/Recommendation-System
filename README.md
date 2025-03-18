# Recommendation System Based on Amazon Reviews

This repository demonstrates how to build a recommendation system using Python, based on Amazon user reviews of products categorized by type. The approaches utilized in this project include:

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

## Getting Started

To get started with this project, clone the repository and follow the instructions provided in the `README.md` file. You'll need to have Python installed along with the necessary libraries.

### Prerequisites

- Python: personally used 3.12.3
- Required Python libraries: Surprise, Scikit-Learn, NLTK, Hugging-face 

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Gabrielonee/Recommendation-System.git

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## Acknowledgements
Python libraries used for data analysis and machine learning
For any questions or feedback, feel free to open an issue or contact the repository owner.
