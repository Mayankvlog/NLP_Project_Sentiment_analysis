# NLP_Project_Sentiment_analysis

This Streamlit web app performs sentiment analysis on both text input and uploaded CSV files using TextBlob and Pandas. Here’s how to use it:

1. **Text Sentiment Analysis**:
   - Enter text in the "Text here" input box to see its polarity and subjectivity scores displayed dynamically.
   - Optionally, enter text in the "Clean Text" input box to view the cleaned version, removing stopwords, punctuation, and more.

2. **CSV Sentiment Analysis**:
   - Use the "Upload file" button to upload a CSV file containing a column of text data (e.g., tweets).
   - The app calculates sentiment polarity for each entry using TextBlob and categorizes them as Positive, Negative, or Neutral based on predefined thresholds.
   - Results are displayed in a table showing the first 10 rows of the processed data.
   - You can download the processed CSV file using the "Download data as CSV" button.

**Dependencies**:
- Ensure you have Python installed with the necessary libraries specified in `requirements.txt`.
- Use Streamlit to run the app locally or deploy it on a server for broader access.

**Usage**:
- Clone the repository.
- Install dependencies (`pip install -r requirements.txt`).
- Run the Streamlit app (`streamlit run app.py`).
