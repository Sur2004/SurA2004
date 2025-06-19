# SurA2004
SARAGA: Carnatic Raga Identification using Audio ML

SARGAM is a machine learning-based system to identify Carnatic ragas from audio samples using feature extraction and a Random Forest classifier. Built using Python, Librosa, and Scikit-learn.

---

## 🚀 Features
- Automatic extraction of MFCCs, chroma, spectral contrast, and ZCR from `.mp3`
- Raga label extraction from `.json` or filename mapping
- Training using Random Forest classifier
- Evaluation with confusion matrix & classification report
- Predict raga for a new `.mp3` file

🚧 Prototype Status – Open to Suggestions!
This project is currently a prototype, focused on experimenting with Carnatic raga identification using audio machine learning techniques.
🔍 What’s working:
Feature extraction from .mp3 using librosa
Raga classification using a Random Forest model
Basic performance evaluation and test predictions
💡 What can be improved:
Support for more ragas and larger datasets
Better accuracy with deep learning models (e.g., CNN, LSTM)
Visualization of pitch contours and note transitions
Real-time raga identification via a web interface
