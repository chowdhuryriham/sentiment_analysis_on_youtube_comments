# Sentiment Analysis on YouTube Comments

This repository demonstrates sentiment analysis performed on YouTube comments using the NLPTown's BERT-based multilingual uncased sentiment analysis model. The code includes the following steps:

## Project Overview

- **1. Install and Import Dependencies:** Installs and imports necessary libraries such as `transformers`, `torch`, `requests`, `beautifulsoup4`, `pandas`, and `numpy`.

- **2. Instantiate Model:** Initializes a BERT-based sentiment analysis model using the `AutoTokenizer` and `AutoModelForSequenceClassification` classes from Hugging Face's Transformers library.

- **3. Encode and Calculate Sentiment:** Demonstrates how to encode a text and obtain sentiment scores from the model.

- **4. Collect Reviews:** Utilizes the YouTube Data API to retrieve comments from a specific YouTube video. The comments are processed and stored in a DataFrame.

- **5. Load Reviews into DataFrame and Score:** Loads the comments into a Pandas DataFrame and performs sentiment analysis on each comment using the BERT-based sentiment analysis model.

## Files

- `Sentiment_analysis.ipynb`: Jupyter Notebook containing the Python code for sentiment analysis on YouTube comments.

## Usage

- To run the code, set up a Python environment with the required dependencies mentioned in the Notebook.

- Add your YouTube Data API key to fetch comments from the desired video by replacing `'AIzaSyAFmImey5MdQd3dX4qXpibPzUhTEF7bxOU'` in the code.

## Acknowledgements

- This project uses NLPTown's BERT-based multilingual uncased sentiment analysis model.
