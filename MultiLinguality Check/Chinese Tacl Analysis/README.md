
# ANLP Final Project - TACL BERT Checkpoint 2: Chinese TACL Analysis

In this Folder, we performed unit test case analysis of tacl bert chinese for the Intra-sentence similarity task using 50k data from Chinese Wikipedia.

## Task Details

To understand how well the TaCL Chinese model performs, unit test case analysis is performed by calculating Intra-sentence Similarity:

1. **Intra-sentence Similarity:** By comparing the pretrained BERT and TACL models' capacities to recognize the semantic similarity between phrases at various layers, intra-sentence similarity analysis can assist in making distinctions between the two models. Therefore, it may be concluded that the models differ in their capacity to capture the semantic similarity across sentences when we calculate intra-sentence Similarity for both models and see if there is a substantial difference in the similarity scores across the two models. We initially determined layer-wise intra-sentence similarity for various sentences provided in 50k sentences from the Chinese Wikipedia in order to do this study. The average similarity score for each layer is then determined by averaging the cosine similarity scores for all phrase pairs in the file divided by the total number of tokens in the file.

## Repository Structure

```
.
├── README.md
├── Chinese_analysis.ipynb
├── requirements.txt
└── data
    └── zh_wiki_randomly_select_50k.txt
```

## Dataset

The dataset used for this analysis is:

- Chinese Wikipedia: `data/zh_wiki_randomly_select_50k.txt`

## Getting Started

1. Clone the repository.
```bash
git clone https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT_Checkpoint_2.git
```

2. Install the required dependencies.
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook `Chinese_analysis.ipynb` and run the cells to perform the Intra-sentence similarity analysis.
