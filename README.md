
# SMS Spam Detection

This project aims to develop a machine-learning model to detect spam messages in SMS text data. It utilizes natural language processing (NLP) techniques and a supervised learning algorithm to classify SMS messages as either spam or non-spam (ham).

## DATASET
The dataset used for this project is the "SMS Spam Collection" from the UCI Machine Learning Repository. It contains a collection of 5,574 SMS messages, labeled as spam or ham. The dataset can be downloaded from Kaggle.

The dataset file (spam.csv) contains two columns:

- `label`: Indicates whether the message is spam (1) or ham (0).
- `text`: The actual text content of the SMS message

## REQUIREMENTS

To run the project, you need the following dependencies:
- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk (Natural Language Toolkit)
- matplotlib

You can install the required packages by running the following command:

```
pip install pandas numpy scikit-learn nltk matplotlib
```

## Usage

1. Clone the repository or download the project files.

2. Place the `SMS text message.csv` file in the project directory.

3. Run the `sms_spam_detection.py` script to train and evaluate the spam detection model.

4. The script will load the dataset, preprocess the text data, and train a machine learning model using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

5. After training, the model will be evaluated on a holdout set and the performance metrics (such as accuracy, precision, recall, and F1-score) will be displayed.

6. Finally, you can use the trained model to predict the label (spam/ham) of new SMS messages by modifying the `predict` function in the script.


## Results

The trained model achieved an **accuracy of 97.30 %** and **Precision is 100 %** on the test set and performed well in terms of precision, recall, and F1-score.
