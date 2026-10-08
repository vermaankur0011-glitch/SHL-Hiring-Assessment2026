# SHL Hiring Assessment 2026

## Project Overview
This project was developed for the SHL Hiring Assessment 2026 competition.

The objective was to build a machine learning model to predict assessment scores from audio data.

## Dataset
- Training samples: 769
- Test samples: 216
- Audio-based features were extracted from the recordings.

## Feature Engineering
Audio features were extracted using:
- MFCC
- Audio statistics
- Spectral features
- Zero Crossing Rate
- Other audio-based features

Final feature size:
- 46 features

## Machine Learning Model

The final model used was:

**ExtraTreesRegressor**

Model configuration:
- n_estimators: 500
- min_samples_leaf: 2
- max_features: 0.8
- random_state: 42

## Validation Results

Validation RMSE: **0.6927**

Validation Pearson Correlation: **0.8615**

## Kaggle Result

Public Kaggle Score: **0.7368**

## Files

- `SHL_Hiring_Assessment_2026.ipynb` — Complete notebook containing data processing, feature extraction, model training and prediction.
- `submission.csv` — Final competition predictions.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Librosa
- SciPy
- Jupyter Notebook
- Kaggle

## Author

**Ankur Verma**
