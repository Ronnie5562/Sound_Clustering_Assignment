# Sound Clustering Project

![Image](https://github.com/user-attachments/assets/d6cc9e9f-2cb8-4054-9dc0-67855710c0a4)

## Overview
This project applies clustering techniques to unlabeled sound recordings using:
- Mel-frequency cepstral coefficients (MFCCs) for feature extraction
- PCA and t-SNE for dimensionality reduction
- K-Means and DBSCAN for clustering

## Requirements
- Python 3.8+
- Libraries: librosa, scikit-learn, matplotlib, seaborn, numpy

## Usage
1. Place audio files in `data/` directory (WAV format recommended)
2. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/sound_clustering.ipynb
   ```

## Key Features
- Feature extraction from audio files

- Visualization of high-dimensional data

- Comparison of clustering algorithms

- Performance evaluation using silhouette scores
