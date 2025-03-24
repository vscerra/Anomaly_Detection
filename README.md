# Anomaly Detection

Network Instrusion Detection with NSL-KDD

This project explores unsupervised anomaly detection using the NSL-KDD dataset, a widely-used benchmark in network intrusion detection.

## 📊 Overview

We use two main approaches:
- **Isolation Forest** as a baseline
- **Autoencoder neural network** for deep anomaly detection

Model performance is compared using metrics like precision, recall, and F1-score across multiple decision thresholds.

## 🔧 Methods

- Data preprocessing and normalization
- Isolation Forest (tree-based)
- Deep Autoencoder (PyTorch)
- Threshold tuning based on reconstruction error
- Final comparison via visualization and metrics

## 📁 Files

- `NSL_KDD_Autoencoder_Anomaly_Detection.ipynb` – Main notebook with models, plots, and results
- `KDDTrain+.txt` – Raw dataset file

## 📈 Results

At optimal threshold (55th percentile):
- F1 Score: 0.9490
- Precision: ~96%
- Recall: ~91%

## 🚀 Future Work

- Try Variational Autoencoders (VAEs)
- Incorporate time-series or sequential models (e.g., LSTM)
- Deploy real-time anomaly scoring

---

## 📚 Dataset Source

[NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)
