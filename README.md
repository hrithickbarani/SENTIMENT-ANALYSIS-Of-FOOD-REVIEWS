# Sentiment Analysis of Product Reviews

## Project Overview
This project performs sentiment analysis on product reviews using Natural Language Processing (NLP) techniques. It utilizes the VADER (Valence Aware Dictionary and Sentiment Reasoner) sentiment analysis tool from the `nltk` library to analyze and visualize sentiment scores associated with different review ratings.

## Dataset
The dataset used in this project is `Reviews.csv`, which contains customer reviews along with their ratings.

## Features Implemented
- Data loading and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Tokenization and Part of Speech (POS) tagging
- Named Entity Recognition (NER)
- Sentiment analysis using VADER
- Visualization of sentiment scores vs. review ratings

## Installation & Setup
To run this project, ensure you have Python installed along with the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn nltk tqdm
```

Additionally, you need to download necessary NLTK datasets:

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('words')
nltk.download('vader_lexicon')
```

## Usage
1. Load the dataset (`Reviews.csv`).
2. Perform Exploratory Data Analysis (EDA) to understand review distributions.
3. Use NLTK for tokenization, POS tagging, and Named Entity Recognition.
4. Apply VADER sentiment analysis to determine the polarity of reviews.
5. Visualize the relationship between sentiment scores and review ratings.

## Key Findings
- Most reviews have a positive sentiment (5-star ratings dominate the dataset).
- Higher review ratings correlate with higher positive sentiment scores.
- Lower review ratings exhibit higher negative sentiment scores.
- VADER sentiment analysis provides reliable insights into customer opinions.

## Visualizations
The project includes bar plots comparing:
- Review ratings distribution
- Sentiment scores (Negative, Neutral, Positive) across different star ratings
- Compound sentiment scores vs. review ratings

## Conclusion
The project successfully demonstrates the effectiveness of sentiment analysis using VADER. The results align with expectations, confirming that higher star ratings tend to have more positive sentiment, and lower ratings exhibit more negativity.

## License
This project is for educational purposes and follows an open-source approach.

## Author
[Hrithick Barani]
[hrithickbarani555@gmail.com]

