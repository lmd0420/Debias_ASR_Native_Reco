# Debias_ASR_Native_Reco
The Impact of Native Speaker Recognition on Enhancing Automatic Speech Recognition


## Introduction
This repository is dedicated to our research on improving Automatic Speech Recognition (ASR) systems for handling different accents in English. Our work addresses the inherent bias in ASR systems towards non-native English speakers by exploring the impact of accents and developing methods to enhance speech recognition quality.

## Repository Structure
- `data/`: Contains the audio database marked with labels for native and non-native English speakers.
- `models/`: Hosts the deep learning models used for classifying native and non-native accents and for fine-tuning ASR systems.
- `scripts/`: Includes scripts for testing ASR systems (Google Cloud Speech, Assembly, Whisper, etc.) and for processing the audio data.

## Dataset
Our dataset is a collection of audio files from both native and non-native English speakers, designed to train and test our models. The data is labeled to distinguish between these two speaker groups. The original recordings are from Kaggle Speech Accent Archive.

## Models
- **Accent Classifier**: A deep learning model that accurately classifies speakers as native or non-native based on their accents.
- **ASR Fine-Tuning**: Models for fine-tuning ASR systems using a balanced dataset of native and non-native speakers.

## Usage
Instructions for setting up the environment, training the models, and running the ASR tests are provided in the respective directories.

## Contributions
- **Audio Database Creation**: We have compiled a unique audio database labeled for native and non-native English speakers.
- **Accent Classification Model**: Developed a model to effectively classify accents, which is critical for assembling balanced training data.
- **ASR System Enhancement**: Demonstrated marked improvement in ASR systems by fine-tuning them with our balanced dataset, as evidenced by reduced Word Error Rates (WER).

## Citation
If you use our data or models in your research, please cite our paper: https://medium.com/@mingdali_76805/striking-a-balanced-dataset-the-role-of-accent-on-enhancing-automatic-speech-recognition-f89f9ea50c10
