# SMS/Email Spam Detector

## Project Overview
The SMS/Email Spam Detector is a machine learning-based project designed to classify messages as either spam or ham (not spam). This project involves data cleaning, exploratory data analysis (EDA), feature extraction, and model building to achieve accurate spam detection.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
Spam detection is a crucial task in the field of natural language processing (NLP). This project utilizes a dataset of SMS messages to train and evaluate a spam detection model. The main steps include data preprocessing, feature extraction, and applying machine learning algorithms to classify the messages.

## Features
- **Data Cleaning:**
  - Dropping unnecessary columns (`Unnamed: 2`, `Unnamed: 3`, `Unnamed: 4`).
  - Renaming columns for clarity (`v1` to `target`, `v2` to `text`).
  - Handling missing values and removing duplicate entries.

- **Exploratory Data Analysis (EDA):**
  - Visualizing the distribution of spam and ham messages.
  - Plotting the percentage of spam and ham messages using pie charts.
  - Analyzing the number of characters, words, and sentences in each message.

- **Feature Extraction:**
  - Calculating the number of characters in each message.
  - Tokenizing the text to count the number of words.
  - Splitting the text into sentences to count the number of sentences.

- **Model Building:**
  - Using machine learning models (details can be customized) to classify messages as spam or ham.
  - Training the model on the preprocessed data.
  - Evaluating the model performance using metrics such as accuracy, precision, recall, and F1-score.

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/spam-detector.git
    cd spam-detector
    ```

2. **Install required packages:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Download the dataset:**
    - Place the `spam.csv` file in the project directory.

## Usage
1. **Run the Jupyter Notebook:**
    - Open `Spam Detection.ipynb` in Jupyter Notebook or Jupyter Lab.
    - Execute the cells sequentially to preprocess the data, perform EDA, extract features, and build the model.

2. **Modify the code:**
    - You can customize the feature extraction and model parameters to improve performance.

## Results
- **Data Distribution:**
    - Visualize the distribution of spam and ham messages using pie charts.
- **Feature Analysis:**
    - Examine the statistical properties of features like the number of characters, words, and sentences.
- **Model Performance:**
    - Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.

## Contributing
We welcome contributions to enhance the project! If you have suggestions or improvements, please fork the repository and submit a pull request.



---

The SMS/Email Spam Detector project is an essential tool for understanding and applying machine learning techniques to real-world data. It aims to provide a comprehensive guide to building and evaluating spam detection models.
