# Sentiment-Analysis-for-Nvidia-Stock
Walkthrough of conducting a sentiment analysis on Nvidia stock against 1800 articles scraped through Google API, built with Python code. 

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Visualizations](#visualizations)
7. [Contributing](#contributing)
8. [Contact Information](#contact-information)

## Introduction
In the rapidly evolving world of financial markets, understanding the sentiment of a stock is pivotal. Our project is a data-driven approach to dissect the sentiment of Nvidia's stocks by leveraging state-of-the-art web scraping, natural language processing, and data visualization. By going through into the nexus between public sentiment and stock performance, this endeavor provides valuable insights for investors, traders, analysts, and researchers.

## Features
- **Robust Data Collection**: Gathering pertinent news articles related to Nvidia from various sources.
- **Intelligent Web Scraping**: Extracting full article text with user-agent simulation.
- **Real-Time Stock Integration**: Loading Nvidia's stock data for comprehensive analysis.
- **Advanced Sentiment Analysis**: Utilizing TextBlob for polarity and subjectivity scoring.
- **Insightful Visualization**: Crafting intuitive visualizations to trace sentiment trends and stock price movements.
- **Modular and Scalable Design**: Extensible codebase adaptable to various stocks and sectors.

## Requirements
- Python 3.x
- GoogleNews
- fake-useragent
- newspaper3k
- pandas
- requests
- openbb
- textblob
- matplotlib

## Installation
```bash
!pip install GoogleNews fake-useragent newspaper3k pandas requests openbb textblob matplotlib
```

## Usage
The complete guide in the blog walks you through each step of the process, including:
- **Environment Setup**: Prepare your environment with the required libraries.
- **Data Collection & Processing**: Gather and preprocess the news articles.
- **Sentiment Analysis**: Evaluate the sentiment from news articles.
- **Stock Data Integration**: Merge sentiment analysis with stock data.
- **Data Visualization**: Visualize the results with customizable graphs.

## Visualizations
- **Sentiment Polarity over Time**: Trace how the polarity of news sentiment changes.
- **Nvidia Closing Price Over Time**: Analyze Nvidia's closing price in relation to sentiment.

## Contributing
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contact Information
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, Sentiment-Analysis-for-Nvidia-Stock.
For a full article walkthrough please visit > (https://www.pyfi.com/blog) < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
