# TP: Word Embeddings for Classification

## Authors:
- Giovanni Benedetti Da Rosa
- Tarcisio Da Silva Bueno

## Objectives:
This project explores various methods to represent textual data and applies them to a small French classification dataset based on professional certification titles (**RNCP**). The aim is to evaluate how different representations perform in a classification task.

## Steps:
1. **Data Pre-processing**: 
   - Clean the dataset.
   - Build an appropriate vocabulary from the textual data.

2. **Textual Representations**: 
   We employ several techniques to convert the documents into vector representations, including:
   - **Symbolic Representations**: 
     - Bag of Words (**BoW**)
     - Term Frequency-Inverse Document Frequency (**TF-IDF**)
   - **Dense Document Representations via Topic Modeling**: 
     - Latent Semantic Analysis (**LSA**)
     - Latent Dirichlet Allocation (**LDA**)
   - **Dense Word Representations**: 
     - Singular Value Decomposition (SVD) reduced Positive Pointwise Mutual Information (**PPMI**)
     - **Word2Vec**
     - **GloVe**
   - For dense word representations, we implemented a function to aggregate word vectors into document vectors.

3. **Classification**:
   - We performed classification using **logistic regression** on the obtained document vectors.

## Dependencies

numpy
matplotlib
pandas

