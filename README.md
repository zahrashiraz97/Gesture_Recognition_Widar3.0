# Gesture_Recognition_Widar3.0 Using Wi-Fi CSI Data and Random Forest

## Overview
This project demonstrates how to process Wi-Fi **Channel State Information (CSI)** data to perform gesture recognition using a **Random Forest** classifier. The dataset consists of `.mat` files containing complex CSI data. The pipeline includes data preprocessing, feature extraction, model training, hyperparameter tuning, and evaluation.

---

## Project Structure
- **Input Data**: CSI data in `.mat` format stored in the directory `train/`.
- **Feature Extraction**: Amplitude and phase features aggregated over time.
- **Model**: Random Forest classifier trained on extracted features.
- **Hyperparameter Tuning**: Grid Search to find the best parameters for the Random Forest model.
- **Evaluation**: Accuracy, precision, recall, and F1-score.

---

## Requirements
- Python 3.8+
- Libraries:
  - `numpy`
  - `scipy`
  - `pandas`
  - `sklearn`

Install dependencies using:
```bash
pip install numpy scipy pandas scikit-learn
