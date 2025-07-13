This project focuses on building a text classification model that predicts the sentiment (positive or negative) of IMDB movie reviews using a Long Short-Term Memory (LSTM) neural network.

Project Highlights
✅ Custom LSTM Model Implementation: Built and trained an LSTM model from scratch using TensorFlow/Keras.

✅ Dataset Collection via Kaggle API: Automated downloading and extraction of the IMDB dataset using Kaggle credentials.

✅ Data Preprocessing Pipeline: Includes tokenization, padding, and splitting data into training and testing sets.

✅ Predictive System: Implemented a function that predicts sentiment for new reviews based on the trained model.


Technologies Used
Python

TensorFlow / Keras

Pandas

Scikit-learn

Kaggle API

How to Run
Set up Kaggle API credentials (kaggle.json) in your project directory.

Install required libraries:

bash
Copy
Edit
pip install kaggle pandas scikit-learn tensorflow
Run the Python script or Jupyter Notebook.

Train the model and evaluate performance.

Use the predict_sentiment() function to classify new review texts.

