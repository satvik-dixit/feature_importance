# Feature Importance
Using feature importance for speech emotion recognition

## Demo files
- `FI_egemaps.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik-dixit/feature_importance/blob/main/FI_egemaps.ipynb) A demo containing the steps for finding feature importance od opensmile egemaps using the CREMA-D dataset. It includes loading and resampling audio files, extracting metadata, extracting egemaps features, speaker normalisation, label separation and calculating feature importance. Feature Importance is calculated using 
  1. permutation importance (model agnostic)
  2. Standard methods
      - logistic regression
      - SVM
      - random forest classification
