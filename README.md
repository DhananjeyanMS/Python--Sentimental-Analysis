# Sentiment Analysis with Naive Bayes and Rule-Based Models

## Introduction
This project implements a sentiment analysis model using both a Naive Bayes classifier and a rule-based sentiment dictionary approach. The model classifies text as either positive or negative based on word occurrences in training datasets. The project explores multiple techniques, such as dictionary-based sentiment analysis and Naive Bayes, to predict sentiment polarity across various datasets, including movie reviews and Nokia-related datasets.

## What It Does
1. **Naive Bayes Model**: 
   - Uses word frequency and conditional probabilities to classify sentences as positive or negative.
   - Trains on a set of pre-labeled movie reviews and tests on unseen data to evaluate accuracy.
   
2. **Rule-Based Dictionary Classifier**:
   - Uses a predefined dictionary of positive and negative words to classify sentences.
   - Considers negations, diminishers, and intensifiers to adjust sentiment scores.
   - Computes performance metrics such as accuracy, precision, recall, and F1 scores for both positive and negative classes.

3. **Advanced Rule-Based Classifier**:
   - Expands the rule-based classifier with additional handling for negation, diminishing, and intensifying words to improve accuracy.

4. **Performance Metrics**:
   - The script outputs evaluation metrics like accuracy, precision, recall, and F1-score to assess model performance for each classification method.

## How to Run

### Prerequisites
Ensure that you have Python installed, along with the following dependencies:
- `re` (Regular expressions)
- `math`
- `collections`
- `itertools`
- Random library

Additionally, you should have the following input files in your working directory:
- `rt-polarity.pos` - Positive movie reviews
- `rt-polarity.neg` - Negative movie reviews
- `nokia-pos.txt` - Positive reviews specific to Nokia
- `nokia-neg.txt` - Negative reviews specific to Nokia
- `positive-words.txt` - Predefined list of positive words
- `negative-words.txt` - Predefined list of negative words

### Running the Code
1. Clone the repository or download the project files.
2. Place the required input files in the project directory.
3. Run the Python script using the following command:

```bash
python sentiment_analysis.py
