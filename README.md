# Airline Review Text Classification and Topic Modeling

## Description

The purpose of this project was to extract online airline reviews from TripAdvisor and SkyTrax using the `playwright` library. Skytrax filters were leveraged to group airlines into different regions, and the airlines with the most reviews for each region were selected for the final dataset. Text classification and topic models were trained using feature sets consisting of only review text and retrained incorporating airline attribute ratings as well. The Linear SVC, Random Forest, and Multinomial Naive Bayes models were trained and tested for accuracy.

## Repository Contents

### Core Project files

`airline_reviews.json`
`data_extraction_cleaning.ipynb`
`topic_modeling_classification.ipynb`

## Methods

- Data Wrangling
  - Web Scraping
  - Playwright
- Exploratory Data Analysis
  - Tokenization
  - Descriptive Statistics
- Text Classification
  - Linear SVC
  - Random Forest
  - Multinomial Naive Bayes
- Topic Modeling
- Sentiment Analysis
- Model Evaluation
  - Accuracy

## Technologies

- Python
- Playwright

## Data Source

- [Skytrax](https://skytraxratings.com/)
- [Trip Advisor](https://www.tripadvisor.com/)
