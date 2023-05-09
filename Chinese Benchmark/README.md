# ANLP Final Project - TACL BERT Checkpoint 2: Chinese Benchmark Analysis

In this Folder, we evaluate the performance of the TaCL Chinese model using five datasets: msra, resume, weibo, ontonotes, and pku. We compute F1 score, precision, and recall metrics for this model on these datasets. Analyzing the results of the TaCL-Chinese benchmark across different datasets provides valuable insights into the model’s performance and potential areas for improvement.

## Task Details

1. **Chinese Benchmark Data Preparation:**
    ```
    chmod +x ./download_benchmark_data.sh
    ./download_benchmark_data.sh
    ```

2. **Conduct inference from author released checkpoints:**
    (1) Downloading checkpoints for all evaluated tasks:
    ```
    chmod +x ./download_checkpoints.sh
    ./download_checkpoints.sh
    ```
    (2) Perform inference on different benchmarks:
    ```
    cd ./sh_folder/inference/
    chmod +x ./inference_{}.sh
    ./inference_{}.sh
    ```
    Here, `{}` is in ['msra', 'ontonotes', 'weibo', 'resume', 'pku', 'cityu', 'as'] and the parameters are described below:
    - `--saved_ckpt_path`: The trained model checkpoint path. Remember to modify it when you train your own model.
    - `--train_path`: Training data path.
    - `--dev_path`: Validation data path.
    - `--test_path`: Test data path.
    - `--label_path`: Data label path.
    - `--batch_size`: Inference batch size.

## Folder Structure

```
.
├── README.md
├── Chinese_Benchmark.ipynb
├── dataclass.py
├── download_benchmark_data.sh
├── download_checkpoints.sh
├── inference.py
├── metric_py3.py
├── model.py
├── requirements.txt
├── train.py
└── sh_folder
    ├── inference
    │   ├── inference_as.sh
    │   ├── inference_cityu.sh
    │   ├── inference_msra.sh
    │   ├── inference_ontonotes.sh
    │   ├── inference_pku.sh
    │   ├── inference_resume.sh
    │   └── inference_weibo.sh
    └── train
        ├── as.sh
        ├── cityu.sh
        ├── msra.sh
        ├── onto.sh
        ├── pku.sh
        ├── resume.sh
        └── weibo.sh
```

## Getting Started

1. Clone the repository.
```bash
git clone https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT_Checkpoint_2.git
```

2. Install the required dependencies.
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook `Chinese_Benchmark.ipynb` and run the cells to perform the Chinese Benchmark Analysis.
