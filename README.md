# voice-biometric-identification-system
Voice biometric identification system for speaker recognition using audio feature extraction and machine learning.
# Voice Biometric Identification System

A Voice Biometric Identification system developed as part of a Pattern Recognition course. The project focuses on recognizing and identifying speakers based on their voice characteristics using machine learning techniques.

## Project Overview
<img width="1875" height="958" alt="Screenshot 2026-06-25 034611" src="https://github.com/user-attachments/assets/769c9e40-7850-4b50-b5b9-a27d058841c4" />
Note: Raw audio dataset and source code are not included due to privacy considerations and university course restrictions.
The system was trained on a custom dataset collected manually from classmates, including both male and female voices in Arabic and English.

The dataset included recordings from:
- Salma
- Dina
- Jawad
- Sofyan
- Ibrahim
- Hammam

This diversity helped simulate real-world variability in speech patterns and accents.

## Features

- Speaker recognition based on voice input
- Support for Arabic and English speech samples
- Custom dataset collection and preprocessing
- Audio feature extraction
- Machine learning classification model

## Feature Extraction

Audio signals were converted into numerical representations suitable for machine learning using feature extraction techniques (e.g., spectral and time-domain features).

These features were used to train a classification model capable of distinguishing between different speakers.

## Challenges

One of the main challenges was overlapping similarity between voice patterns, which occasionally led to misclassification (e.g., identifying one speaker as another).

This highlighted the complexity of voice biometrics and the sensitivity of audio-based classification systems.

Despite this, the project provided valuable insight into:

- Audio processing pipelines
- Feature extraction from speech signals
- Limitations of classical machine learning in biometric tasks

## Team Project

Developed collaboratively with Dina Al-Shamayleh as part of a university Pattern Recognition course.

## Technologies

- Python
- Librosa / Audio Processing
- NumPy
- Scikit-learn
- Machine Learning (Classification Models)

## Learning Outcomes

- Understanding voice biometrics systems
- Handling real-world noisy datasets
- Feature engineering for audio signals
- Building end-to-end ML pipelines
