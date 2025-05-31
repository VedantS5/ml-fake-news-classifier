# Fake News Detection Using Machine Learning

A machine learning-based system that detects fake news articles by analyzing text content patterns and linguistic features. This project implements various NLP techniques and classification algorithms to identify misinformation in news articles with high accuracy.

## Project Structure

- **Application**: Contains the Flutter-based mobile application system
- **implementation**: Contains model files, scripts, and classification logic including Flask API
- **python notebooks**: Contains Jupyter notebooks for data analysis and model development

## Features

- Fake news detection using machine learning algorithms
- Text analysis and feature extraction
- Classification of news articles
- Sentiment analysis
- Political affiliation detection
- Clickbait detection
- Toxicity analysis
- Spam filtering

## Setup and Installation

### Prerequisites
- Python 3.7+
- Flutter SDK (for mobile application)
- Android Studio/emulator

### API Setup
1. Navigate to the `implementation` folder
2. Install required packages: `pip install -r requirements.txt`
3. Run the Flask API: `python imp.py`

### Mobile App Setup
1. Open the `Application/fake_news_detectio_system` folder in Android Studio
2. Run the application on an emulator
3. For port forwarding: `adb reverse tcp:5000 tcp:5000`

For more details, please refer to the `How to run.txt` file.

## Technologies Used

- Python
- Flask (API)
- Flutter (Mobile Application)
- Machine Learning (Classification models)
- Natural Language Processing
- XGBoost
- Scikit-learn
- Sentiment Analysis
- Feature Engineering

## License

This project is open source and available under the MIT License.
