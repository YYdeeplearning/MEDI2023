# Understanding Mobile Game Reviews Through Sentiment Analysis: A Case Study of PUBGm

This project designs a comprehensive framework that employs topic modeling and sentiment analysis to extract insightful keywords from a vast collection of reviews. The experiment was conducted on a dataset containing six million English reviews collected up to March 2023 for the mobile game PUBGm from Google Play.

## Requirements for running the experiment

* python 3.7.3
* pytorch 1.2.0
* transformers 4.1.1
* numpy 1.16.4
* tensorboardX 1.9
* tqdm 4.32.1

The codes are derived from: Yu, Y., Dinh, D. T., Nguyen, B. H., Yu, F., & Huynh, V. N. (2023). Mining Insights from Esports Game Reviews with an Aspect-Based Sentiment Analysis Framework. IEEE Access.

## Requirements for LDA

* python 3.7.3
* gensim 4.0.1
* spacy 3.0.6

  ```bash
  python -m spacy download en_core_web_sm
  ```

* scipy 1.6.2

## Dataset

The collected dataset can be downloaded at: https://shorturl.at/BEWY5

## Environment

* OS: Ubuntu 20.04.2 LTS
* GPU: NVIDIA A40
* CUDA: 10.0
* cuDNN: v7.6.1
