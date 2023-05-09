# ANLP TaCL BERT SQuAD Robustness Check

This Folder contains the implementation of robustness of the TaCL BERT model finetuned for the Stanford Question Answering Dataset (SQuAD) task. We perform a comprehensive evaluation using the award-winning CheckList methodology and focus on various robustness dimensions. The results are analyzed and discussed in detail to understand the strengths and weaknesses of the model in handling real-world data perturbations.
The Checklist is a framework designed to evaluate the performance of natural language processing (NLP) models across a wide range of linguistic capabilities. In the given list, several linguistic phenomena and aspects are mentioned. Below, we provide descriptions of each and then give examples of the three main types of tests used in the Checklist framework: MFT (Minimum Functionality Test), INV (Invariance Test), and DIR (Directional Expectation Test).

The repository includes two options for running the project:

1. A Jupyter Notebook called `ANLP_TACL_BERT_Squad_Robustness_Check.ipynb`.
2. A Google Colab Notebook available at [this link](https://colab.research.google.com/drive/1L4G4vDVSalVI2ZqTW3Ti0UxA80ofjz2W?usp=sharing).

Both notebooks contain the same content and can be used to train and evaluate the Tacl BERT model on the SQuAD dataset.

## Getting Started

To get started with the project, follow the instructions below:

### Prerequisites

Ensure that you have the following software installed on your system:

- Python 3.6 or later
- Jupyter Notebook (if using the local notebook)
- Git
- checklist
### Data Download 
Download the Dataset required for the checklist from https://drive.google.com/drive/folders/1Q9vnPO0g-rwgROWFwx3coaIhH33dbiSk?usp=share_link
### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT_Checkpoint_2.git
```
2. Navigate to the cloned repository:

3. Install the required Python packages using pip:
```bash
pip install -r requirements.txt

```
## Running the Local Notebook
1. Launch Jupyter Notebook:
```
jupyter notebook
```
2. Open the ANLP_TACL_BERT_Squad_Robustness_Check.ipynb  notebook from the Jupyter Notebook interface.

3. Follow the instructions in the notebook to train and evaluate the BERT model on the SQuAD dataset.

## Running the Google Colab Notebook
1. Open the Google Colab Notebook.

2. If you have a Google account, save a copy of the notebook to your Google Drive by clicking File > Save a copy in Drive.

3. Follow the instructions in the notebook to train and evaluate the BERT model on the SQuAD dataset.

