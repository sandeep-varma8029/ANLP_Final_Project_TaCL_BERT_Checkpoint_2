# ANLP Final Project - TACL BERT Checkpoint 2: Multilabel Sentence-level Classification

This Folder contains the work done for the multilabel sentence-level classification task using the TACL BERT model.We trained the model on four languages: French, Korean, Telugu, and Hindi, using subsets of the Wiki dataset translated into these languages.We performed experiments on the TACL BERT-based models and the BERT-base Multilingual model for multilabel sentence-level classification tasks. We used an annotated dataset from Homework 2 (HW2) with 15 labels corresponding to different news article categories, which were translated into the respective languages for the TACL models.

## Dataset Preparation

The original dataset contained news articles labeled with one or more of the 15 categories. To create language-specific datasets for the TACL models, the news articles were translated into the target languages: Hindi, Telugu, Korean, and French.

## Repository Structure

```
.
├── README.md
├── Multilabel_sentence_level_Classification_Task.ipynb
├── helpers.py
├── requirements.txt
└── data
    ├── french_hw2.csv
    ├── hindi_hw2.csv
    ├── korean_hw2.csv
    └── telugu_hw2.csv
```

## Dataset

The dataset used for this analysis consists of the following CSV files:

- French: `data/french_hw2.csv`
- Hindi: `data/hindi_hw2.csv`
- Korean: `data/korean_hw2.csv`
- Telugu: `data/telugu_hw2.csv`

## Getting Started

1. Clone the repository.
```bash
git clone https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT_Checkpoint_2.git
```

2. Install the required dependencies.
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook `Multilabel_sentence_level_Classification_Task.ipynb` and run the cells to perform the multilabel sentence-level classification.
