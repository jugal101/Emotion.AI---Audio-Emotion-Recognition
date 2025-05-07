Emotion.AI - Audio Emotion Recognition
This repository contains the code and resources for an Audio Emotion Recognition project using the TESS (Toronto Emotional Speech Set) dataset. The project consists of a Jupyter Notebook for training the emotion recognition model and a Python script for building a graphical user interface (GUI) application.
Features
Trains a deep learning model to classify emotions from audio files
Provides a user-friendly GUI for audio analysis and emotion prediction
Displays prediction results with corresponding emojis
Maintains a history of predictions for reference

Dataset
The project uses the TESS (Toronto Emotional Speech Set) dataset, which contains 2800 audio files of two female actresses portraying seven emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
You can download the dataset from Kaggle: https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

Prerequisites
Before running the project, ensure you have the following installed:
Python 3.x
pip
Libraries: numpy, tensorflow, librosa, tkinter, pandas, sklearn
You can install the required libraries using pip:

pip install numpy tensorflow librosa tkinter pandas scikit-learn

Project Structure
Speech_Emotion_Detection_TESS.ipynb: Jupyter Notebook for training the emotion recognition model
emotion_model.keras: Trained emotion recognition model (will be generated after training)
EmotionApp.py: Python script for the GUI application
emojis/: Directory containing emoji images for each emotion

Author 
Jugal Mistry
