# KIAM - Financial News Dataset Analysis

A comprehensive analysis of financial news articles to extract insights on publication patterns, topics, and publisher characteristics.

## Dataset

- **Size:** 1,407,328 articles
- **Features:** headline, url, publisher, date, stock
- **Source:** `data/raw_analyst_ratings.csv`

## Project Structure

```
KIAM/
├── data/              # Dataset files
├── notebooks/         # Jupyter notebooks for analysis
├── scripts/          # Utility scripts
├── src/              # Source code
└── tests/            # Test files
```

## Analysis Components

### Task-1: Exploratory Data Analysis (Complete)
- **Descriptive Statistics:** Headline length, publisher counts, publication trends
- **Text Analysis:** Keyword extraction, bigrams, event detection, LDA topic modeling
- **Time Series Analysis:** Publication frequency, temporal patterns, spike detection
- **Publisher Analysis:** Contribution analysis, email domain extraction

### Task-2: Advanced Analysis (In Progress)
- Publisher-specific news type analysis
- Stock price correlation analysis
- Sentiment analysis integration

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download NLTK data:
   ```python
   import nltk
   nltk.download('stopwords')
   ```

## Usage

Open and run the Jupyter notebook:
```bash
jupyter notebook notebooks/row_anlysis_eda.ipynb
```

## Key Findings

- Identified 10 distinct topics through LDA analysis
- Detected temporal patterns in publication timing
- Found significant publisher concentration
- Identified publication spikes potentially linked to market events

## Requirements

See `requirements.txt` for full list. Main dependencies:
- pandas, numpy
- matplotlib, seaborn
- nltk, scikit-learn
- jupyter

## License

[ 