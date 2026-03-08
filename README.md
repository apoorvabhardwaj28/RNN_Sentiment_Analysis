# RNN for Sentiment Analysis

This project performs sentiment analysis on the IMDB movie reviews dataset using a Recurrent Neural Network (RNN) implemented in PyTorch.

The notebook demonstrates the complete workflow including data preprocessing, feature extraction, dataset preparation, and model training for binary sentiment classification.

## Dataset

The dataset used is the **IMDB Movie Reviews Dataset**, which contains movie reviews labeled as:

- Positive
- Negative

## Data Preprocessing

The following preprocessing steps were applied to the text data:

- Converting text to lowercase
- Removing URLs
- Removing punctuation
- Removing HTML tags
- Removing stopwords
- Stemming using Porter Stemmer

## Feature Extraction

Text data was converted into numerical features using:

- **TF-IDF Vectorization**

This allows the model to process textual input in numerical form.

## Model

A **Recurrent Neural Network (RNN)** implemented in **PyTorch** was used for sentiment classification.

The model was trained on the processed review data to classify sentiments as positive or negative.

## Training Pipeline

1. Load and clean dataset
2. Apply text preprocessing
3. Convert text to TF-IDF features
4. Split dataset into train and test sets
5. Create PyTorch DataLoaders
6. Train the RNN model
7. Evaluate performance on test data

## Tech Stack

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Project Structure
