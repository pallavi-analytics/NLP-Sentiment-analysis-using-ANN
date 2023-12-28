# SENTIMENT ANALYSIS OF DRUG REVIEWS USING ARTIFICIAL NEURAL NETWORKS

### Overview
This repository contains the code and resources for a sentiment analysis project focused on analyzing drug reviews. The dataset is a combination of two sources: WebMD and UCI Machine Learning Repository, merged and preprocessed to create a comprehensive dataset for sentiment analysis.

### Data Preprocessing
Null Values Handling: Checked and addressed null values in the dataset.
Column Names: Altered column names for consistency and clarity.
Ratings Treatment: Modified the ratings column for further analysis.

### Sentiment Labeling
Converted Ratings to Sentiments: Ratings were transformed into positive and negative sentiments for sentiment analysis.

### Exploratory Data Analysis (EDA)
Balance Check: Investigated whether the dataset is balanced in terms of positive and negative sentiments.
Stopwords Removal: Utilized NLTK to remove common stopwords from the text data.
Word Cloud Analysis: Visualized common occurring words in reviews using Word Cloud.

### Feature Engineering
One-Hot Encoding: Performed one-hot encoding to prepare the data for input into the sentiment analysis model.

### Artificial Neural Network (ANN) Model
Developed an Artificial Neural Network using TensorFlow Keras.
Activation Functions: Explored and compared the performance of different activation functions.
Accuracy Comparison: Evaluated the model's accuracy for each activation function.

### Result
Simple classifier: Training Accuracy:0.5540 and Testing Accuracy:0.5541

ANN Model with 'relu'activation function:Training Accuracy:0.7995 and Testing Accuracy:0.7568

ANN Model with more layers and 'tanh' activation function:Training Accuracy: 0.7333 and Testing Accuracy: 0.7305

