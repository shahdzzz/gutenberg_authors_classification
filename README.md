
# Gutenberg Authors Classification Project

## Overview

The **Gutenberg Authors Classification** project aims to classify texts from different nationalities but of the same genre using machine learning techniques. The project involves collecting five different books from the Gutenberg website, preprocessing the texts by removing stop words, dividing each book into partitions of 150 words, and implementing various machine learning models for classification. The models considered for this project include Support Vector Machines (SVM), Random Forest, Naïve Bayes, k-Nearest Neighbor, XG-Boost, and Logistic Regression. Additionally, the project explores the use of BERT for text classification and evaluates the performance of the models through cross-validation.

## Dataset

The dataset consists of five books collected from the Gutenberg website. These books belong to the same genre but are written by authors of different nationalities. The books are:

1. **Pride and Prejudice** by Jane Austen
   - [Read Online](https://www.gutenberg.org/cache/epub/1342/pg1342.txt)

2. **Anna Karenina** by Leo Tolstoy
   - [Read Online](https://www.gutenberg.org/cache/epub/1399/pg1399.txt)

3. **Little Women or Meg, Jo, Beth, and Amy** by Louisa M. Alcott
   - [Read Online](https://www.gutenberg.org/cache/epub/37106/pg37106.txt)

4. **Wuthering Heights** by Emily Brontë
   - [Read Online](https://www.gutenberg.org/cache/epub/768/pg768.txt)

5. **This Side of Paradise** by F. Scott Fitzgerald
   - [Read Online](https://www.gutenberg.org/files/805/805-0.txt)

## Preprocessing

1. Text Collection: The books are downloaded from the Gutenberg website and stored as plain text files.

2. Stop Word Removal: Common stop words are removed from the text to reduce noise and improve feature extraction.

3. Partitioning: Each book is divided into partitions of 150 words. A total of 200 partitions are created per book.

## Feature Extraction

Three different techniques are used for feature extraction:

1. **Bag of Words**: This method converts the text into a matrix of word counts.

2. **TF-IDF (Term Frequency-Inverse Document Frequency)**: This method considers the importance of each word in the context of the entire corpus.

3. **N-grams**: N-grams capture the relationship between words in a sequence, helping to retain context.

## Machine Learning Models

Several machine learning models are implemented for classification:

1. Support Vector Machines (SVM) with probability estimates enabled.
2. Random Forest Classifier.
3. Naïve Bayes Classifier (Gaussian).
4. k-Nearest Neighbor Classifier with 5 neighbors.
5. XG-Boost Classifier.
6. Logistic Regression Classifier.

## Cross-Validation

Cross-validation is performed to evaluate the performance of the models. This involves splitting the dataset into training and testing sets multiple times to obtain reliable performance metrics.

## BERT Integration

The project also explores the use of BERT (Bidirectional Encoder Representations from Transformers) for text classification. BERT is a powerful pre-trained language model that can capture complex linguistic relationships.

## Usage

1. Clone the repository and navigate to the project directory.
2. Ensure you have the required Python libraries installed. You can use `pip` to install them.
3. Run the preprocessing script to clean and partition the texts.
4. Run the feature extraction scripts for Bag of Words, TF-IDF, and N-grams.
5. Run the different classification models and evaluate their performance using cross-validation.
6. Optionally, explore the BERT-based classification script for comparison.

## Conclusion

The **Gutenberg Authors Classification** project demonstrates the application of various machine learning models for classifying texts from different nationalities within the same genre. By preprocessing the text, extracting meaningful features, and implementing a range of classification models, the project aims to achieve accurate genre classification. Additionally, the project delves into the potential of BERT-based classification for further enhancement.

For any inquiries or suggestions, please contact [shahd mohamed] at [shahdmohamed67777@gmail.com].
