# Music Genre Classification using Deep Learning

A deep learning project that classifies music genres from audio clips using **CNN-LSTM** and **Bidirectional GRU** architectures. The project leverages mel-spectrogram representations generated with **Librosa** and compares multiple neural network models for accurate genre prediction.

---

## Overview

Music genre classification is a supervised learning task that involves identifying the genre of an audio track based on its acoustic features. This project builds an end-to-end pipeline covering audio preprocessing, feature extraction, model development, training, evaluation, and inference.

The objective is to explore deep learning techniques for audio understanding while comparing different sequential architectures for classification performance.

---

## Features

- Audio preprocessing using **Librosa**
- Mel-spectrogram feature extraction
- CNN-LSTM model for spatial and temporal feature learning
- Bidirectional GRU model for sequence modeling
- Data preprocessing and normalization
- Experiment tracking using **Weights & Biases**
- Model evaluation using Accuracy and F1-score
- Prediction generation on unseen audio samples

---

## Tech Stack

- Python
- PyTorch
- Librosa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Weights & Biases (W&B)

---

## Project Workflow

```
Audio Dataset
      │
      ▼
Audio Preprocessing
      │
      ▼
Mel-Spectrogram Generation
      │
      ▼
Feature Extraction
      │
      ▼
Deep Learning Models
(CNN-LSTM / BiGRU)
      │
      ▼
Training & Validation
      │
      ▼
Performance Evaluation
      │
      ▼
Prediction
```

---

## Deep Learning Models

### CNN-LSTM

- Convolutional Neural Networks extract spatial patterns from mel-spectrograms.
- Long Short-Term Memory (LSTM) networks capture temporal dependencies within audio sequences.
- Suitable for learning both local and sequential audio characteristics.

### Bidirectional GRU

- Processes sequences in both forward and backward directions.
- Captures long-range contextual information efficiently.
- Offers lower computational complexity than LSTMs while maintaining strong performance.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- F1 Score
- Validation Loss

These metrics provide a balanced assessment of classification performance across multiple genres.

---

## Repository Structure

```
├── final-notebook.ipynb
├── README.md
├── requirements.txt
├── models/
├── data/
└── outputs/
```

---

## Skills Demonstrated

- Audio Signal Processing
- Deep Learning
- Feature Engineering
- Data Preprocessing
- Neural Network Design
- Model Evaluation
- Experiment Tracking
- Machine Learning

---

## Future Improvements

- Transformer-based audio classification models
- Data augmentation for improved generalization
- Hyperparameter optimization
- Model deployment using Streamlit or FastAPI
- Real-time music genre prediction

---

## Author

**Saket Kumar**

- GitHub: https://github.com/saket-kumar14

---

