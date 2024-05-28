# Email Spam Detection

## Overview

This Jupyter Notebook project focuses on classifying emails as either spam or ham (non-spam) using the Naive Bayes algorithm. Naive Bayes is a widely used algorithm for text classification tasks, making it suitable for spam detection. The project preprocesses the email data, calculates word frequencies, and then applies Naive Bayes to classify new emails.

(Note: The project implements the Naive Bayes algorithm from scratch, without relying on external libraries such as scikit-learn.)

## Features

- Preprocesses email data: The notebook preprocesses email data by removing stopwords, punctuation, and converting words to lowercase.
- Calculates word frequencies: It calculates the frequency of each word in the dataset, categorized as spam or ham.
- Implements Naive Bayes: The Naive Bayes algorithm is implemented to classify new emails as spam or ham based on word frequencies.

## Dependencies

- Python 3.12.3
- NLTK (Natural Language Toolkit) library
- Pandas
- NumPy

## File Structure

- `Email_Spam_Detection_Naive_Bayes.ipynb`: Jupyter Notebook containing the project code and explanations.
- `emails.csv`: Email dataset.
- `README.md`: Documentation about the project.
