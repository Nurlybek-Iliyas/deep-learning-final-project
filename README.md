# Week 1 Report


This week, I selected the project topic: Fake News Detection.
I also chose the dataset from Kaggle (Fake and Real News Dataset).

I created a GitHub repository with the required structure, including folders for data, notebooks, src, reports, and results.

I downloaded and loaded the dataset using Python and pandas.
Then I performed exploratory data analysis (EDA).

## Dataset Analysis

The dataset contains around 45,000 news articles.
Each sample includes a title, text, subject, and date.

I checked:

* number of samples in each class (fake vs real)
* text length distribution
* missing values

The dataset is relatively balanced and has no major missing values.

## Experiments and Results

At this stage, no model was trained yet.
The focus was on understanding the dataset.

## Problems / Challenges

* Large text size requires preprocessing
* Some articles are very long
* Need to decide how to combine title and text

## Plan for Next Week

* Perform text preprocessing (cleaning, tokenization)
* Convert text to numerical format (TF-IDF)
* Train a baseline model (Logistic Regression)
* Evaluate using accuracy and F1-score
