# ANLP Final Project - TACL BERT Checkpoint 2

This project builds upon a paper [TaCL: Improving BERT Pre-training with Token-aware Contrastive Learning](https://arxiv.org/abs/2111.04198) that presents TaCL (Token-aware Contrastive Learning) , a revolutionary continuous pre-training technique that promotes BERT  to learn a token representation distribution that is isotropic and discriminative. TaCL is completely unsupervised and does not require any further data.

Many current language models that have been pre-trained with MLM objectives suffer from anisotropy }. That is, their token representations are limited to a small subset of the representation space, making them less discriminative and less effective at capturing the semantic distinctions between unique tokens.

The central claim of the paper talks about how TaCL's continual pre-training approach aims to encourage BERT to learn an isotropic and discriminative distribution of token representations. The paper we based our study on focuses on how TaCL's continuous pre-training approach can promote BERT to learn an isotropic and discriminative distribution of token representations. However, the paper does not explore robustness evaluation or testing the model on multiple languages, nor does it perform any checklist to evaluate the model's behavior.

To address these gaps in the original paper, we focused primarily on robustness and multilinguality by using the [Beyond Accuracy: Behavioral Testing of NLP models with CheckList](http://homes.cs.washington.edu/~marcotcr/acl20_checklist.pdf)   and its accompanying code and python package. We evaluated the model's performance on this checklist and explored the usage of the Multilingual Checklist to perform behavioral testing on all languages we worked with.

Overall, our study builds upon the baseline implementation of TaCL BERT to explore these new dimensions. By testing the model's robustness and performance in multiple languages, we have taken a step towards more comprehensive and applicable NLP models.

## Repository Structure

```
.
├── README.md
├── Chinese Benchmark
├── MultiLinguality Check
└── Robustness check
```

### Chinese Benchmark
In this Folder, we evaluate the performance of the TaCL Chinese model using five datasets: msra, resume, weibo, ontonotes, and pku.. The instructions to run the experiment can be found in this folder.

### MultiLinguality Check
This folder contains the experiments and analysis conducted for multilingual sentiment analysis and multilabel sentence-level classification tasks using the TACL BERT model trained on four languages: French, Korean, Telugu, and Hindi. The instructions to run the experiments can be found in this folder.

### Robustness check
This folder contains the experiments and analysis conducted to evaluate the robustness of the TACL BERT model. The instructions to run the experiments can be found in this folder.

## Baseline Implementation
Please refer to the [Baseline Implementation Repository](https://github.com/sandeep-varma8029/ANLP_Final_Project_TaCL_BERT/tree/master) for the base implementation of the TaCL BERT model.

# Project Team Memebers:
1. Sai Sandeep Varma Mudundi (G01352322)
2. Asra Naseem (G01349680)
3. Rajeev Priyatam Panchadula (G01333080)
