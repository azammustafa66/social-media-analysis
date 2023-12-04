
# Social Media Sentiment Analysis

## Overview

This Jupyter notebook is focused on sentiment analysis, specifically applied to movie reviews. It includes data cleaning, user input processing, vectorization, and sentiment classification using Multinomial Naïve Bayes.

## Contents

1. **Data Cleaning**: The notebook starts with a section dedicated to cleaning the dataset used for sentiment analysis.
2. **User Input**: This section deals with processing input from the user.
3. **Vectorization**: The notebook then moves on to vectorize the processed data.
4. **Sentiment Classification**: The final section uses the Multinomial Naïve Bayes method for classifying sentiments.

## Key Code Snippets

1. **Data Initialization**: The notebook initializes the training data with movie reviews and their corresponding sentiments.

    ```python
    # Existing data
    X_train = ["This was really awesome an awesome movie", ...]
    ```

2. **Library Imports and Setup**: Essential libraries are imported, and NLTK stopwords are downloaded for text processing.

    ```python
    import re
    import nltk
    from nltk.tokenize import RegexpTokenizer
    ```

3. **Data Pre processing Function**: A function is defined for text cleaning and pre processing.

    ```python
    # Data Preprocessing and Tokenization
    ```

4. **Test Data Initialization**: Test data with new movie reviews are initialized for testing the model.

    ```python
    X_test = ["it was average but I loved the plot", "the movie was groundbreaking and had amazing visuals", ...]
    ```

## How to Use

To use this notebook for sentiment analysis:

1. Ensure you have the required libraries installed (`nltk`, etc.).
2. Run each cell sequentially, starting from data initialization to the sentiment classification.
3. You can modify the test data (`X_test`) to analyse different movie reviews.

## Requirements

- Python 3.x
- NLTK library
- Additional libraries as per the import statements in the notebook.
