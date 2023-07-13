# Email Spam Classifier

This is a simple email spam classifier built using python in Jupyter Notebook.
It takes emails and their labels as inputs and builds a vocabulary and a bow represantion of the emails.
Then, it uses the SVM and K-NN models available in nltk library to learn and then predict whether an email is
classified as spam or not spam. It also print the accuracy and AUC score of the predicted values by comparing them to the original labels and produces 3 plots one each reflecting the frequency of unique words in all mails, only spam mails and
only non-spam mails respectively.

## Requirements

1) Python 3.10 or newer.
2) NumPy,sklearn,nltk,matplotlib Python libraries.
3) Jupyter Notebook support.

## Execution

Run each cell sequentially and wait for completetion of execution of one cell before moving to another.