# AI Legal Sentiment Analyzer

A sentiment analysis tool that classifies the emotional tone of legal 
documents — case summaries, court rulings, and compliance reports — 
as positive, negative, or neutral using IBM watsonx.

## How It Works
1. Legal text documents are preprocessed and cleaned (removing noise, 
   normalizing text).
2. The processed text is passed through IBM watsonx's language model 
   for sentiment classification.
3. Each document is labeled as positive, negative, or neutral based 
   on the model's output.
4. Results are compared against a labeled dataset to evaluate accuracy.

## Tech Stack
- Python
- IBM watsonx.ai
- Pandas / NumPy for data handling

## Dataset
`legal_sentiment_dataset.csv` — a labeled dataset of legal document 
excerpts with corresponding sentiment tags used for evaluation.

## Setup
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `legal_sentiment_analysis.ipynb` in Jupyter
4. Run all cells to reproduce results

## Future Improvements
- Expand dataset size for better generalization
- Add a simple UI/dashboard for non-technical users
