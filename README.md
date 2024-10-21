# Studio-per-la-realizzazione-di-Recommender-Systems-analisi-e-valutazione-di-modelli-di-Text-Mining

This project implements various text mining models to develop a content-based movie recommender system. The goal is to compare and evaluate different approaches to build a high-quality system capable of assisting users in movie selection by providing personalized recommendations.

# Table of Contents:

Overview

Data

Models

Count Vectorizer

TF-IDF

Bag of Words

Word2Vec

BERT

Results

# Overview:

This repository contains the implementation of a content-based recommender system using various text mining and natural language processing (NLP) models. The recommender system analyzes movie descriptions and metadata to recommend similar films based on user input. The models implemented include:

Count Vectorizer

TF-IDF (Term Frequency-Inverse Document Frequency)

Bag of Words

Word2Vec

BERT (Bidirectional Encoder Representations from Transformers)

The main objective is to assess and compare the performance of each model in generating meaningful and personalized movie recommendations.

Data:

The dataset used in this project is sourced from TMDb (The Movie Database), containing 5000 of the top-rated movies. It includes movie metadata such as title, description, genres, and crew.

# Models:

Count Vectorizer:

Converts the text into a matrix of token counts, helping to find similarity between movies based on word frequency.

TF-IDF:

Calculates the importance of words by considering their frequency across the entire corpus, leading to more refined movie recommendations.

Bag of Words:

Represents movie descriptions as a collection of words, ignoring grammar and word order, but capturing term frequency.

Word2Vec:

Generates word embeddings that capture semantic meaning, allowing for more sophisticated recommendations based on the context of words in the description.

BERT:

A transformer-based model that deeply understands context, used for generating powerful sentence embeddings to find movie similarities.

# Results:

Each model was tested to generate recommendations for the movie The Lord of the Rings: The Fellowship of the Ring. Here are the key findings:

Count Vectorizer: Captured genre-specific recommendations well but struggled with nuanced context.

TF-IDF: Provided context-aware suggestions with better relevance to movie plots.

Word2Vec: Successfully captured semantic similarity between films, offering high-quality recommendations.

BERT: Achieved the best results, understanding the deep context and generating highly accurate and personalized recommendations.
