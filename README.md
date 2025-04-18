# 🎙️ Speech Emotion Recognition (SER)

A Deep Learning-based system that recognizes human emotions from speech using LSTM and MFCC features. This project leverages the TESS dataset and classifies emotions such as angry, happy, sad, fear, disgust, pleasant surprise, and neutral.

## 🔍 Overview

The goal of this project is to detect the emotional tone behind a speaker's voice. This has applications in areas like customer service, mental health monitoring, virtual assistants, and human-computer interaction.

The model is built using:
- LSTM Neural Network
- MFCC (Mel Frequency Cepstral Coefficients) features
- TESS (Toronto Emotional Speech Set) Dataset

## 🧠 Model Architecture

- Input: MFCC feature vectors extracted from audio
- Layers:
  - LSTM layers for sequential data processing
  - Dense layers for classification
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

## 🗂️ Dataset

**Toronto Emotional Speech Set (TESS)**  
It includes speech samples of 7 emotions:  
`angry`, `disgust`, `fear`, `happy`, `neutral`, `pleasant surprise`, and `sad`.

Dataset link: [TESS Dataset on Toronto's official website](https://tspace.library.utoronto.ca/handle/1807/24487)






<!---
S61203/S61203 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
