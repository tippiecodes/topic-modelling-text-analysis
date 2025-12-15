# Topic Modelling with NLP

This project explores **topic modelling** techniques to identify latent themes within a corpus of text data using unsupervised learning.

## Overview
Large text datasets often contain hidden patterns that are difficult to surface through manual reading. This project applies topic modelling to discover recurring themes and semantic structures within text, supporting exploratory analysis and insight generation.

## Key Techniques
- Text cleaning and normalization
- Tokenization, lemmatization, and stopword removal
- Document–term matrix construction
- Latent Dirichlet Allocation (LDA)
- Topic coherence and interpretability analysis
- Visualisation of topic distributions and keywords

## Data Preparation
Raw text data was processed through multiple preprocessing stages to improve topic quality and reduce noise, including:
- Lowercasing and punctuation removal
- Stopword filtering
- Lemmatization
- Frequency-based filtering

## Outcome
The topic modelling process surfaced distinct, interpretable themes within the dataset, demonstrating how unsupervised NLP methods can be used to structure and summarise large collections of unlabelled text.

## Tech Stack
Python, scikit-learn, gensim, NLTK, pandas, matplotlib, pyLDAvis

## Notes
This repository focuses on exploratory text analysis and topic discovery rather than downstream classification or deployment.
