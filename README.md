# Sentiment Analysis Dashboard

## Overview

This project is an AI/ML-powered dashboard for sentiment analysis of user-input text. It leverages a labeled dataset (`sentimentdataset.csv`) containing social media posts and their associated sentiments to train and evaluate sentiment classification models. The dashboard allows users to input text and receive real-time sentiment predictions, providing insights into emotional tone and trends.

---

## Features

- **Text Sentiment Prediction:** Enter any text and receive an instant sentiment classification (e.g., Positive, Negative, Neutral, or more nuanced emotions).
- **Data Visualization:** Visualize sentiment distribution, trends over time, and other analytics based on the dataset.
- **Model Training & Evaluation:** Train machine learning models using the provided dataset and evaluate their performance.
- **User-Friendly Interface:** Intuitive dashboard for both technical and non-technical users.

---

## Dataset: `sentimentdataset.csv`

The dataset is a CSV file containing real-world social media posts labeled with sentiment categories. Each row represents a unique post with various metadata.  
**Key columns include:**

- `id`: Unique identifier for each entry
- `text`: The content of the social media post
- `sentiment`: Labeled sentiment (e.g., Positive, Negative, Neutral, or specific emotions like Joy, Gratitude, Anger, etc.)
- `datetime`: Timestamp of the post
- `username`: User or poster's handle
- `platform`: Social media platform (e.g., Twitter, Facebook, Instagram)
- `hashtags`: Associated hashtags
- `likes`, `shares`: Engagement metrics
- `country`: Country of origin
- `year`, `month`, `day`, `hour`: Date and time breakdown

**Example row:**
```
263,267,"Gratitude as a guiding star, navigating the constellation of blessings in the vast universe of life's precious moments.",Grateful,2022-03-12 19:55:00,StarNavigator,Twitter,#Grateful #GuidingStar,19.0,38.0,Australia,2022,3,12,19
```

---

## How It Works

1. **Data Preprocessing:** The dataset is cleaned and prepared for model training (tokenization, stopword removal, etc.).
2. **Model Training:** Machine learning or deep learning models are trained on the labeled data.
3. **Prediction:** User input is processed and passed to the trained model for sentiment prediction.
4. **Visualization:** Results and analytics are displayed on the dashboard.

---

## Getting Started

1. **Clone the repository**
2. **Install dependencies** (see `requirements.txt`)
3. **Run the dashboard application** (typically via `python app.py` or similar)
4. **Interact with the dashboard** in your browser

---

## Requirements

- Python 3.x
- Common ML libraries: pandas, scikit-learn, numpy, matplotlib, etc.
- Web framework: Streamlit, Flask, or Dash (depending on implementation)

---

## Usage

- Launch the dashboard.
- Enter text in the input field.
- View the predicted sentiment and related analytics.

---

## License

This project is for educational and research purposes.

---

## Acknowledgements

- The dataset (`sentimentdataset.csv`) is curated for sentiment analysis research and includes diverse, real-world social media content.