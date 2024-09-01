# Book Popularity Prediction Model

## Project Overview

This project aims to develop a machine learning model that predicts whether a book will be popular or not for an online bookstore. The model utilizes various features of books and their reviews to make these predictions, supporting the bookstore in stock control and revenue generation.

## Dataset

The dataset includes the following features for each book:

- Price
- Review summary
- Review text
- Review helpfulness
- Authors
- Categories
- Popularity (target variable)

## Methodology

1. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical features

2. **Feature Engineering**:
   - Extract features from review text (e.g., sentiment, length)
   - Create author popularity metrics
   - Develop category-based features

3. **Model Development**:
   - Split data into training and testing sets
   - Train and evaluate multiple models (e.g., Random Forest, Gradient Boosting)
   - Perform hyperparameter tuning

4. **Model Evaluation**:
   - Achieve target accuracy of at least 70%
   - Analyze feature importance
   - Conduct cross-validation for robustness

## Tools Used

- Python
- Pandas for data manipulation
- Scikit-learn for model development
- NLTK or spaCy for natural language processing
- Matplotlib/Seaborn for data visualization