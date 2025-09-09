# RNN Movie Sentiment Review Analysis

A Recurrent Neural Network (RNN) based project for analyzing movie reviews and classifying their sentiment. This repository contains code and resources to train and evaluate an RNN model that predicts whether a movie review is positive or negative.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Results](#results)

---

## Project Overview

This project implements a sentiment analysis model using Recurrent Neural Networks (RNNs) to classify movie reviews as positive or negative. The model is trained on a labeled dataset of movie reviews and can be used to predict the sentiment of new reviews.

---

## Features

- Preprocessing of movie review text data
- Tokenization and padding of sequences
- RNN model implementation using popular deep learning frameworks
- Training and evaluation scripts
- Visualization of training progress and results
- Ready-to-use for sentiment prediction on movie reviews

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/NotJEEtard-18/RNN-Movie-Sentiment-Review-Analysis.git
   cd RNN-Movie-Sentiment-Review-Analysis
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Prepare your dataset or use the provided dataset.

2. Run the training script:

   ```bash
   python train.py
   ```

3. Evaluate the model on test data:

   ```bash
   python evaluate.py
   ```

4. Use the model to predict sentiment on new reviews:

   ```bash
   python predict.py --review "Your movie review text here"
   ```

---

## Model Architecture

- Embedding layer to convert words into dense vectors
- Recurrent layers (e.g., LSTM or GRU) to capture sequential dependencies
- Fully connected output layer with sigmoid activation for binary classification

---

## Dataset

The model is trained on a dataset of movie reviews labeled with positive or negative sentiment. The dataset is preprocessed by cleaning, tokenizing, and padding sequences to a fixed length.

---

## Results

The model achieves competitive accuracy on the test set, demonstrating effective sentiment classification of movie reviews.

---
