# Sentiment Analysis on Tweets

## Project Description

This project involves performing sentiment analysis on Twitter data using machine learning techniques. The goal is to classify tweets as either **positive**, **negative**  based on their content. We used **Logistic Regression** with the **TF-IDF** (Term Frequency-Inverse Document Frequency) vectorization method for text preprocessing and training the model.

## Technologies Used

- **Python**
- **Google Colab** (for running the notebook)
- **Natural Language Toolkit (NLTK)**
- **Scikit-learn**
- **Pandas**


## Dataset

The dataset used in this project consists of labeled tweets. It contains tweets collected from Twitter, and each tweet has been labeled as **positive**, **negative**.

You can either use a pre-existing dataset or collect the data through the Twitter API.

## How the Project Works

### 1. **Data Preprocessing**

The dataset is first preprocessed by:
- Removing unnecessary characters, special symbols, and links.
- Converting text to lowercase.
- Removing stopwords (commonly used words that do not add significant meaning).
- Stemming the words using **Porter Stemming** to reduce words to their root form.

### 2. **Feature Extraction**

We convert the preprocessed tweets into numerical data using **TF-IDF Vectorization**, which calculates the importance of words in the dataset.

### 3. **Model Training**

- **Train-Test Split**: The data is split into training and testing sets (80% train, 20% test).
- **Logistic Regression Model**: A logistic regression classifier is trained on the training set using the vectorized features.

### 4. **Model Evaluation**

The model's performance is evaluated using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

### 5. **Prediction**

Once the model is trained, it can predict the sentiment of unseen tweets.

## Steps to Run the Project

### 1. **Clone the Repository**
Clone this repository to your local machine:

