# Stock Market Prediction using Reddit Sentiment Analysis

The python version used in this project is 3.12. This project aims to predict stock market movements by analyzing sentiment data extracted from Reddit posts. It combines web scraping, sentiment analysis, and machine learning to create a stock movement prediction model.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Setup and Installation](#setup-and-installation)
4. [How to Run the Project](#how-to-run-the-project)
5. [File Structure](#file-structure)

---

## Overview
The repository contains:
- **Well-documented code** for web scraping and building a machine learning model.
- A **Jupyter notebook** demonstrating:
  - Data scraping.
  - Sentiment preprocessing.
  - Model training and evaluation.

This project uses Python libraries like `Pandas` , `PRAW`, `Tensorflow` and `scikit-learn` to scrape data, extract features, and build the model.

---

## Features
- **Reddit Scraper**: Extracts text data from Reddit posts.
- **Sentiment Analysis**: Determines sentiment polarity of the posts using a sentiment analysis library.
- **Stock Prediction**: Builds and evaluates a predictive model for stock market movements based on extracted sentiment data.

---

## Setup and Installation
Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sanjay22ai/stock-market-prediction-using-reddit-sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock-market-prediction-using-reddit-sentiment-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run the Project

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook stock-prediction-reddit-sentiment-analysis.ipynb
   ```
2. Follow the steps in the notebook:
   - Scrape the Reddit data.
   - Preprocess the text for sentiment analysis.
   - Train the stock prediction model.
   - Evaluate the model's performance.

---

## File Structure

- **README.md**: Project documentation.
- **stock-prediction-reddit-sentiment-analysis.ipynb**: Main Jupyter notebook containing data scraping, data preprocessing and analysis, and stock price prediction code.
- **requirements.txt**: List of dependencies for the project.

