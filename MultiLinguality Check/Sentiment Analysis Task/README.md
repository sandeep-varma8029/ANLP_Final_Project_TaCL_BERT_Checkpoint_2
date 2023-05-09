# ANLP Final Project - TACL BERT Checkpoint 2: Multilingual Sentiment Analysis

This Folder contains the work done for the multilingual sentiment analysis task using the TACL BERT model. We trained the model on four languages: French, Korean, Telugu, and Hindi, using subsets of the Wiki dataset translated into these languages. We used the model for sentiment analysis task, and compared the performance of TACL BERT-based models with BERT-base multilingual uncased models.

## Repository Structure

```
.
├── README.md
├── Sentiment_Analysis_Task.ipynb
├── requirements.txt
└── data
    ├── french.csv
    ├── hi_3500.csv
    ├── korean.csv
    └── telugu.csv
```

## Dataset
Dataset: The dataset used for this analysis was based on the Hindi reviews BERT dataset (https://github.com/mapmeld/hindi-bert/blob/latest/hi_3500.csv), which consists of 3,500 sentences for sentiment analysis. This dataset was translated into Telugu, Korean, and French to test the performance of the respective models.
The dataset used for this analysis consists of the following CSV files:

- French: `data/french.csv`
- Hindi: `data/hi_3500.csv`
- Korean: `data/korean.csv`
- Telugu: `data/telugu.csv`

## Getting Started

1. Clone the repository.
```bash
git clone https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT_Checkpoint_2.git
```

2. Install the required dependencies.
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook `Sentiment_Analysis_Task.ipynb` and run the cells to perform the sentiment analysis.
