# Semantic Analysis of Tourist Reviews

This project applies Natural Language Processing (NLP) techniques to analyze tourist reviews from different destinations around the world.

## Objectives
- Automatically generate sentiment labels using weak supervision (VADER)
- Train classical machine learning models for sentiment classification
- Compare multiple models and perform hyperparameter tuning
- Discover common themes using topic modeling (LDA)
- Analyze sentiment distribution across locations
- Validate results using a pretrained transformer model (BERT)

## Dataset
Tourist Review Dataset containing textual reviews and locations.

Data is loaded directly from a GitHub raw link inside the notebook.

## Methods
- Text preprocessing (cleaning, lowercasing, tokenization)
- TF-IDF vectorization with unigrams and bigrams
- Logistic Regression
- Support Vector Machine (SVM)
- Hyperparameter tuning (GridSearchCV)
- Topic Modeling (LDA)
- Optional transformer-based sentiment analysis (BERT)

## Best Model
Support Vector Machine (SVM)  
Accuracy: 91%

## Files
- travel_reviews_nlp_project.ipynb – main notebook
- data/Tourist Review.csv – dataset

