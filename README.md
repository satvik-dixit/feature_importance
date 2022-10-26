# Feature Importance
Feature importance for speech emotion recognition

## Demo files
- `FI_egemaps.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik-dixit/feature_importance/blob/main/FI_egemaps.ipynb) A demo containing the steps for finding feature importance od opensmile egemaps using the CREMA-D dataset. It includes loading and resampling audio files, extracting metadata, extracting egemaps features, speaker normalisation, label separation and calculating feature importance. 
Feature Importance is calculated using:
  1. Permutation Importance (model agnostic)
  2. Standard methods
      - `coef_` for logistic regression
      - `coef_` for support vector machine
      - `feature_importances_` for random forest 
      
- `FI_all_emotions.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik-dixit/feature_importance/blob/main/FI_all_emotions.ipynb) A demo to use the pipeline function for determining the feature importances for all emotions of the CREMA-D dataset (Angry, Happy, Fear, Sad and Disgust).
 
