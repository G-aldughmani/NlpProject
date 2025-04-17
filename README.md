Project: Automated Customer Reviews Analysis
Overview

This project focuses on analyzing customer reviews of Amazon products using natural language processing (NLP) techniques. The goal is to classify reviews into sentiment categories (Positive, Neutral, Negative) based on their star ratings and perform exploratory data analysis (EDA) to understand the data distribution.

Project Structure

The notebook is organized into the following main sections:

Dataset Import
Downloads and combines three Amazon product review datasets from Kaggle
Keeps only relevant columns: 'reviews.rating' and 'reviews.text'
Data Preprocessing
Combines multiple datasets into one DataFrame
Handles missing values
Maps star ratings to sentiment categories:
1-2 stars → Negative
3 stars → Neutral
4-5 stars → Positive
Balances the dataset across all rating categories
Exploratory Data Analysis (EDA)
Examines general information about the data
Shows descriptive statistics
Checks for missing values
Visualizes sentiment distribution
Creates word clouds for each sentiment category
Text Preprocessing
Applies stemming to the review text using Porter Stemmer
Key Features

Uses TF-IDF vectorization for text analysis
Implements sentiment analysis based on product ratings
Includes comprehensive data visualization
Balances the dataset to prevent bias in analysis
Dependencies

The project requires the following Python libraries:

pandas
scikit-learn
seaborn
matplotlib
re
string
nltk (for stemming)
wordcloud
Usage

Ensure all dependencies are installed
Run the notebook cells sequentially
The analysis includes:
Correlation matrix between ratings and sentiment
Count plots of sentiment distribution
Word cloud visualizations
Results

The analysis provides insights into:

The distribution of review sentiments
Common words in positive, neutral, and negative reviews
The relationship between star ratings and sentiment classifications

Note

The notebook downloads datasets from Kaggle, so you'll need valid Kaggle API credentials configured in your environment.
