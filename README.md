**Movie Review Sentiment Classification**

This repository contains a script for classifying movie reviews as either "positive" or "negative" sentiment using a Naive Bayes machine learning model. 
The project demonstrates the essential steps of a machine learning pipeline, including data preprocessing, model training, and evaluation.

**Overview**

The script performs the following tasks:

Loads a dataset of movie reviews and their corresponding sentiments from a CSV file.

Preprocesses the text data to convert it into numerical format using CountVectorizer.

Splits the dataset into training and testing sets.

Trains a Naive Bayes classifier to predict sentiment.

Evaluates the model's accuracy on the test set.

Includes an interactive function to classify custom movie reviews.

**Input File**

Source : https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

The script requires a CSV file with the following structure:

review

sentiment

The column review contains the movie reviews (text).

The column sentiment contains the corresponding labels (positive or negative).

**How to Run the Script in Google Colab**

1. Open Google Collab Environment (https://colab.research.google.com/)
2. Goto File -> Upload Notebook -> select the Script file (.ipynb) and upload
3. Select Table of Contents(Three line stack Symbol)-> Files(Folder Icon) -> Upload to Session Storage (File icon with upward Arrow)
Upload the Input File
Upload the CSV file (e.g., 10_Movies_list.csv) to your Google Colab environment.

4. Run the Script
Execute the cells step by step.

**What does the script do:**

Install Libraries: Import essential libraries like pandas, scikit-learn, and others required for data handling and model building.

Get Data Sets: Load the CSV file containing movie reviews and their corresponding sentiments (positive/negative).

Preprocess the Data: Extract the review (text) and sentiment (labels) columns for further processing.

Split into Training and Testing Sets: Divide the dataset into training and testing sets for model training and evaluation.

Convert Text to Numerical Format Using CountVectorizer: Transform text reviews into numerical vectors for machine learning using CountVectorizer.

Train Classifier - Use the Naive Bayes Classifier for Text Classification: Train a Multinomial Naive Bayes model on the vectorized training data.

Evaluate the Model - Check the Accuracy on the Test Set: Test the model's performance on the test set and calculate its accuracy.

Interactive Prediction - Function to Classify a Movie Review: Define a function to classify new reviews based on the trained model.

Test the Function: Use the classification function to predict the sentiment of a custom review and display the result.

**Input**

Type a review in the Section - Test the Function

test_review = "The movie is Good"

**Output**

Interactive Prediction: The script outputs the predicted sentiment (positive or negative) for the input review.
