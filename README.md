# Twitter-Sentimental-analysis-with-LSTM

# Sentiment Analysis with LSTM

This repository contains a Jupyter Notebook that demonstrates sentiment analysis using an LSTM model. The notebook covers the following steps:

**1. Data Collection and Preparation:**

*   Loads Twitter and Reddit data from CSV files.
*   Combines the datasets and performs data cleaning, including:
    *   Removing URLs, HTML tags, mentions, and numbers.
    *   Handling stop words, punctuation, and alphanumeric characters.
    *   Lemmatization.

**2. Data Preprocessing:**

*   Splits the data into training and testing sets.
*   Uses `Tokenizer` to convert text data into sequences.
*   Pads sequences to ensure uniform length.

**3. Model Building and Training:**

*   Builds an LSTM model using Keras with an embedding layer, LSTM layer, and dense layer.
*   Compiles the model with `categorical_crossentropy` loss and the `adam` optimizer.
*   Trains the model using the training data and validates it with the testing data.
*   Implements early stopping to prevent overfitting.

**4. Model Evaluation:**

*   Evaluates the model's performance using metrics like accuracy.
*   Visualizes the training history to understand the learning process.
*   Generates a classification report to assess precision, recall, and F1-score.

**5. Model Saving:**

*   Saves the trained model for future use.

**Requirements:**

*   Python 3.x
*   Libraries: pandas, numpy, matplotlib, seaborn, nltk, tensorflow, scikit-learn
*   WordNet dataset

**Usage:**

1.  Clone the repository.
2.  Install the required libraries.
3.  Upload the datasets to your Google Drive or modify the file paths accordingly.
4.  Open and run the Jupyter Notebook in Google Colab.

**Note:** Make sure to download the necessary NLTK resources (e.g., stopwords, wordnet) before running the notebook.

This project provides a comprehensive example of sentiment analysis using an LSTM model. You can adapt and extend this code for your own sentiment analysis tasks.
