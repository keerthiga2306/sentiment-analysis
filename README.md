#sentiment Analysis
# Sentiment Analysis using Streamlit & Hugging Face

## Project Overview

Sentiment Analysis is a simple and interactive web application built using **Python, Streamlit, and Hugging Face Transformers**. The application analyzes a user-entered sentence and predicts whether the sentiment is **Positive** or **Negative**. It also displays the confidence score of the prediction using a pre-trained DistilBERT model.

## Project Objective

The main objective of this project is to demonstrate how **Natural Language Processing (NLP)** and **Transformer models** can be used to automatically classify the sentiment of text through an easy-to-use web application.

## Features

* Analyze the sentiment of English text
* Positive and negative sentiment detection
* Confidence score display
* Interactive Streamlit interface
* Fast prediction using a pre-trained Hugging Face model
* Efficient model loading with Streamlit caching
* Beginner-friendly implementation

## Technologies Used

* Python
* Streamlit
* Hugging Face Transformers
* PyTorch
* DistilBERT

## Model Information

**Model:** `distilbert-base-uncased-finetuned-sst-2-english`

This pre-trained DistilBERT model is fine-tuned on the **SST-2 (Stanford Sentiment Treebank)** dataset for English sentiment classification. It predicts one of two labels:

* POSITIVE
* NEGATIVE

## Project Structure

```text
Sentiment-Analysis/
│
├── app.py
├── requirements.txt
└── README.md
```

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/Sentiment-Analysis.git
```

### Step 2: Open the project folder

```bash
cd Sentiment-Analysis
```

### Step 3: Install the required libraries

```bash
pip install -r requirements.txt
```

## Requirements

Create a `requirements.txt` file containing:

```text
streamlit
transformers
torch
```

## Run the Application

Run the following command in the terminal:

```bash
streamlit run app.py
```

The application will automatically open in your web browser.

## How It Works

1. Open the Streamlit application.
2. Enter a sentence in the text area.
3. Click **Analyze Sentiment**.
4. The Hugging Face model processes the text.
5. The application displays the predicted sentiment and confidence score.

## Example 1

**Input**

```text
I really enjoyed this movie!
```

**Output**

```text
Sentiment: POSITIVE
Confidence: 99.82%
```

## Example 2

**Input**

```text
I did not like this product.
```

**Output**

```text
Sentiment: NEGATIVE
Confidence: 98.64%
```

## Future Enhancements

* Multi-language sentiment analysis
* CSV file upload
* Batch sentence analysis
* Sentiment visualization
* Downloadable analysis reports
* Sentiment history

## Limitations

* Supports English text only
* Classifies only Positive and Negative sentiments
* Sarcasm and complex expressions may reduce prediction accuracy
* Initial model loading requires downloading the pre-trained model

## Learning Outcomes

* Natural Language Processing (NLP)
* Sentiment Analysis
* Hugging Face Transformers
* Pre-trained AI models
* Streamlit web application development
* Python for AI applications

## Author

**Keerthiga K U**

B.Sc. Computer Science with Artificial Intelligence

SDNB Vaishnav College for Women

