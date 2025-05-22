# Implementation Documentation

This directory contains the Flask API and all the related model files that power the fake news detection system.

## Overview

The implementation consists of:

1. A Flask API (`imp.py`) that serves as the entry point
2. Multiple detection modules:
   - Toxicity detection
   - Spam detection
   - News classification
   - Sentiment analysis
   - Stance detection
   - Political affiliation detection
   - Clickbait detection
   - Domain credibility

## API Usage

The API accepts POST requests with JSON payloads containing:

```json
{
  "title": "News article title",
  "text": "News article content",
  "url": "Source URL of the article"
}
```

## Model Files

- `Classification.pkl`: Main classification model
- `Classificationt_catlabel.pkl`: Category labels for classification
- `Classificationtf.pkl`: TF-IDF vectorizer for classification
- `Spam_filename.pkl`: Spam detection model
- `cblr2.pkl`: Clickbait detection model
- `fold.pkl`: Feature extraction model
- `mnb.pkl`: Multinomial Naive Bayes model
- `tf.pkl`: Text feature extraction

## Running the API

```bash
python imp.py
```

The API will run on port 5000 by default and can be accessed via HTTP requests.

## Dependencies

All required dependencies are listed in the root `requirements.txt` file.
