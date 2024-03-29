Run this command in the terminal before the first run -> **pip install wordcloud nltk selenium**  

# YouTube Comments Sentiment Analysis

This Flask web application performs sentiment analysis on YouTube video comments. It allows users to enter a YouTube video URL and analyzes the sentiment of the comments associated with that video. The sentiment analysis is performed using the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon.

## Features

- Analyze sentiment of YouTube video comments
- Generate word cloud based on cleaned comments
- Display statistics of sentiment analysis results

## Requirements

- Python 3.x
- Flask
- Selenium
- NLTK (Natural Language Toolkit)
- BeautifulSoup4
- Matplotlib
- WordCloud

## Installation

1. Clone the repository:


2. Navigate to the project directory:
cd YouTube-Comments-Sentiment-Analysis


3. Install the required dependencies:
pip install -r requirements.txt


4. Download NLTK corpora:
python -m nltk.downloader vader_lexicon
python -m nltk.downloader stopwords
python -m nltk.downloader wordnet


5. Download Chrome WebDriver and place it in your system PATH or specify its path in the code.

## Usage

1. Run the Flask web application:
python app.py


2. Access the application in your web browser at `http://localhost:5000`.

3. Enter a YouTube video URL and submit the form to analyze the sentiment of its comments.


#   Y o u T u b e - C o m m e n t s - S e n t i m e n t - A n a l y s i s  
 #   Y o u T u b e - C o m m e n t s - S e n t i m e n t - A n a l y s i s  
 