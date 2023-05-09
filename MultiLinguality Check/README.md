# ANLP Final Project - TACL BERT Checkpoint 2: MultiLinguality Check

In this Folder, we trained the TACL model on four languages, namely French, Korean, Telugu, and Hindi, using subsets of the Wiki dataset translated into these languages. We created Hugging Face models for each language and used the model for sentiment analysis and text classification tasks.

## Hugging Face Models

- French: https://huggingface.co/sandeepvarma99/tacl-french
- Korean: https://huggingface.co/sandeepvarma99/tacl-korean
- Telugu: https://huggingface.co/sandeepvarma99/tacl-telugu
- Hindi: https://huggingface.co/sandeepvarma99/tacl-hindi

## Structure

```
.
├── README.md
├── Chinese Tacl Analysis
│   ├── Chinese_analysis.ipynb
│   ├── data
│   │   └── zh_wiki_randomly_select_50k.txt
│   └── requirements.txt
├── Multilabel sentence-level Classification Task
│   ├── Multilabel_sentence_level_Classification_Task.ipynb
│   ├── data
│   │   ├── french_hw2.csv
│   │   ├── hindi_hw2.csv
│   │   ├── korean_hw2.csv
│   │   └── telugu_hw2.csv
│   ├── helpers.py
│   └── requirements.txt
└── Sentiment Analysis Task
    ├── Sentiment_Analysis_Task.ipynb
    ├── data
    │   ├── french.csv
    │   ├── hi_3500.csv
    │   ├── korean.csv
    │   └── telugu.csv
    └── requirements.txt
```
