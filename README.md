Medical Text Classification Using NLP and Deep Learning
Project Overview

This project focuses on Medical Text Classification using Natural Language Processing (NLP) and Deep Learning techniques. The notebook processes medical/customer review text data, performs preprocessing and exploratory analysis, and applies multiple machine learning and deep learning models for text classification.

The project compares traditional NLP models with advanced neural network architectures including:

Naive Bayes
Simple RNN
LSTM
Bidirectional LSTM (BiLSTM)

The goal is to analyze medical-related textual data and classify text effectively using different NLP approaches.

Dataset Information

The dataset contains:

7570 rows
3 columns
Textual comments/reviews along with additional customer information

Each row represents a customer review or medical text sample used for classification tasks.

Features
Text preprocessing and cleaning
Stopword removal
Tokenization
NLP pipeline implementation
Exploratory Data Analysis (EDA)
Word frequency analysis
WordCloud visualization
Machine Learning model implementation
Deep Learning model comparison
Performance evaluation using accuracy metrics and confusion matrix
Technologies Used
Programming Language
Python
Libraries and Frameworks
Pandas
NumPy
Matplotlib
NLTK
Scikit-learn
TensorFlow
Keras
WordCloud
PIL
Models Implemented
1. Naive Bayes

A probabilistic machine learning classifier commonly used in text classification tasks.

2. Simple RNN

A Recurrent Neural Network capable of processing sequential text data.

3. LSTM

Long Short-Term Memory networks designed to capture long-term dependencies in textual sequences.

4. Bidirectional LSTM (BiLSTM)

Processes text in both forward and backward directions for improved contextual understanding.

Project Workflow
Import required libraries
Load and inspect dataset
Perform text preprocessing
Remove stopwords and punctuation
Tokenize and vectorize text
Train machine learning and deep learning models
Evaluate model performance
Compare results across models
Visualize outputs and insights
Exploratory Data Analysis

The project includes:

Distribution analysis
Text length analysis
Word frequency analysis
WordCloud visualization
Data visualization using charts and plots
Deep Learning Techniques Used

The notebook applies several neural network architectures:

Embedding layers
Sequential modeling
Recurrent Neural Networks
LSTM layers
Bidirectional LSTM layers
Dense layers
Dropout regularization
Results

The project demonstrates how deep learning models such as LSTM and BiLSTM can improve text classification performance compared to traditional machine learning approaches.

Key observations:

NLP preprocessing significantly improves classification quality
Sequential models capture contextual relationships in text
BiLSTM provides better contextual understanding for complex text patterns
