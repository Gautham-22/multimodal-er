# Emotion Recognition Project

## Introduction
Welcome to the Emotion Recognition Project! This project explores various approaches to emotion recognition, combining text and audio data for a nuanced understanding of human emotions. We have implemented and trained models using state-of-the-art architectures such as BERT for text, ResNet34, and AlexNet for audio, and explored multimodal combinations for enhanced accuracy.

## Project Structure

### Folders:

1. intermediaries/
   This directory contains several intermediary processed CSV files, some half-trained models, pre-processed files, and other interim artifacts.

2. notebooks/
   This directory holds the project notebooks categorized into subdirectories:
   - audio/
     Audio-Based ER with ResNet34.ipynb: Implementation and training of Audio-Based Emotion Recognition using ResNet34.
     Audio-Based ER with AlexNet.ipynb: Implementation and training of Audio-Based Emotion Recognition using AlexNet.
   - text/
     Text-Based ER with BERT.ipynb: Implementation and training of Text-Based Emotion Recognition using BERT.
   - combined/
     Multimodal ER with BERT and ResNet34.ipynb: Implementation and training of Multimodal Emotion Recognition combining BERT and ResNet34.
     Multimodal ER with BERT and AlexNet.ipynb: Implementation and training of Multimodal Emotion Recognition combining BERT and AlexNet.
   ResNet Data Preparation.ipynb: Notebook for preparing data for training the ResNet34 model.

models: https://drive.google.com/drive/folders/1uv7yXWQK4aMeDmF6wt1ghUDYYp2tQFpG?usp=sharing
This directory contains subdirectories for each model type:
- audio/
  model_audio_new_opt.pt: Trained AlexNet model for Audio-Based Emotion Recognition.
  audio_based_er_resnet34.pkl: Trained Resnet34 model for Audio-Based Emotion Recognition.
- text/
  model_text.pt: Trained BERT model for Text-Based Emotion Recognition.
- combined/
  model_multimodal_bert_resnet34.pt: Trained Multimodal model combining BERT and ResNet34.
  model_multimodal_bert_alexnet.pt: Trained Multimodal model combining BERT and Alexnet.

Usage
Feel free to explore the notebooks and utilize the trained models for emotion recognition tasks.
