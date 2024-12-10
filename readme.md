# Dialect Classification using Wav2Vec2

This project focuses on building and training a machine learning model to classify regional dialects from audio files using **Wav2Vec2**, a state-of-the-art pre-trained model for speech processing. The model is trained on labeled audio data and evaluated for its accuracy in classifying dialects.

---

## Project Description

The goal of this project is to classify dialects from audio recordings using deep learning techniques. It leverages the **Wav2Vec2** model from the Hugging Face Transformers library for feature extraction and fine-tuning. This project aims to contribute to digital forensics and language recognition tasks by enabling automatic dialect classification for better insights and forensic evidence collection.

---

## Features

- **Wav2Vec2-based architecture**: Utilizes pre-trained speech models for high accuracy.
- **Support for multiple dialects**: Trains on labeled data for dialect identification.
- **Data preprocessing**: Handles audio resampling, padding, and truncation.
- **Logging**: Logs training and validation losses/accuracies for each epoch.
- **Early stopping**: Prevents overfitting during training.

---

## Prerequisites

- Python 3.8+
- GPU (optional but recommended for faster training)
- `pip` to install dependencies

---

## Installation

### Step 1: Clone the Repository
Clone the project repository from your source control platform:
```bash
git clone <repository_url>
cd <repository_name>

### Step 2: Set Up Virtual Environment

Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
