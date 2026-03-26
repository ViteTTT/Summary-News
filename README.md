# Summary news

This project uses Natural Language Processing (NLP) techniques to generate concise and meaningful summaries from news articles, helping users quickly capture key information.

# Structure
- `summary_news.ipynb`: Original notebook
- `src/Data_preprocessing`: Data loading and preprocessing
- `Tokenization and padding`: Tokenization and padding
- `src/Model`: Model definition
- `src/Train`: Training script
- `src/Model Evaluation`: Evaluation script
- `src/Predictive model`: Predictive model definition
- `src/Test`: Run test project

# Summary-News — Automatic News Summarization

Summary-News leverages modern Natural Language Processing (NLP) to automatically generate concise, informative summaries from news articles. The project aims to help users quickly grasp the most important information from long-form news content and can be extended into apps for news aggregation, personalised briefings, or research assistance.

# Model & Dataset

Base model: Transformer-based sequence-to-sequence model finetuned for summarization.

Input / Tokenization: Standard subword tokenization with configurable max input length.

Dataset: [Preprocessed news articles](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail?select=cnn_dailymail).

Output: Short abstractive summaries.

### Results
| Metric | Score |
|--------|--------|
| Accuracy | 73.4% |
| Recall | 68.3% |
