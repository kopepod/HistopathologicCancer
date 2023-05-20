# Histopathologic Cancer Detection

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MQs39ViMHjRSj5etjsODLK2c3VtGFwGl)
[![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/competitions/histopathologic-cancer-detection)

<img src="https://github.com/kopepod/HistopathologicCancer/blob/f5e2e9a3c81243e96ba1d2fce5044429c2fc9420/header.png" width="100%" height="100%" />

This repository comprises a jupyter file to classify histopathological images into cancirogen and not cancirogen, brief details:

1. The challenge is a binary classidication problem to compare CNN models and parameters tunning.
2. The dataset comprises 220025 training labeled images and 57458 unlabeled images to rank the methods via the challenge. Follow the kaggle link for more details.
3. We tested several existing pre-trained models and two own architectures.

Here are the best results using only the training set and a  80/20 split.

| Model      | Accuracy |
|------------|----------|
| RS-18      | 0.85     |
| MLP_C3P3F3 | 0.83     |
