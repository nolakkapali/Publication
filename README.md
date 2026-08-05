# Sentiment Analysis of Facebook and YouTube Bengali Comments Using LSTM and Bi-LSTM

This repository contains the implementation of our IEEE conference paper on Bengali sentiment analysis using deep learning models. The study investigates the effectiveness of Long Short-Term Memory (LSTM) and Bidirectional Long Short-Term Memory (BiLSTM) networks for classifying Bengali social media comments into **Positive**, **Negative**, and **Neutral** sentiment classes.

> **Publication:**
> **Sentiment Analysis of Facebook and YouTube Bengali Comments Using LSTM and Bi-LSTM**
> *13th International Conference on Computing, Communication and Networking Technologies (ICCCNT), IEEE, 2022*
> **DOI:** https://doi.org/10.1109/ICCCNT54827.2022.9984395

---

## Overview

Social media platforms contain a large volume of user-generated Bengali text expressing opinions on various topics. This project applies deep learning techniques to automatically classify Bengali comments collected from Facebook and YouTube into sentiment categories.

The study compares the performance of **LSTM** and **BiLSTM** models and demonstrates the effectiveness of sequence-based neural networks for Bengali sentiment classification.

---

## Dataset

* Approximately **4,000** Bengali comments
* Sources:

  * Facebook
  * YouTube
* Classes:

  * Positive
  * Negative
  * Neutral

> **Note:** The dataset is not included in this repository due to usage and distribution restrictions.

---

## Methodology

The workflow includes:

* Data cleaning and preprocessing
* Text tokenization using Keras
* Sequence padding
* LSTM model development
* Bidirectional LSTM (BiLSTM) model development
* Model training and evaluation

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Results

* Developed both **LSTM** and **BiLSTM** models for Bengali sentiment classification.
* Compared model performance using standard evaluation metrics.
* Achieved **97.25% classification accuracy** using the **BiLSTM** model.

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## Repository Structure

```
├── notebooks/
├── models/
├── results/
├── images/
├── requirements.txt
└── README.md
```

---

## Citation

If you find this work useful, please cite:

```
N. Kapali et al., "Sentiment Analysis of Facebook and YouTube Bengali Comments Using LSTM and Bi-LSTM," 2022 13th International Conference on Computing, Communication and Networking Technologies (ICCCNT), 2022.

DOI: 10.1109/ICCCNT54827.2022.9984395
```
