# Image Captioning with Deep Learning

This project implements Image Captioning model that automatically generates natural language descriptions for images using deep learning techniques. It combines a Convolutional Neural Network (CNN) for image feature extraction and a Long-Short Term Memory (LSTM) for sequence generation.

To check out the deployed model click [here](https://image-captioning-gnpfrcat4blxekxkpaw4dq.streamlit.app/)


## Project Overview
* CNN encoder (e.g., ResNet, InceptionV3) for extracting image features
* RNN decoder (e.g., LSTM) with attention mechanism for generating captions
* Attention Mechanism for focusing on important parts of the image
* Tokenizer for word-level processing
* Beam Search / Greedy Search for caption generation
* BLEU score evaluation

## Dataset
Trained and evaluated on the Flickr8k dataset. Can be adapted to any captioned image dataset with minimal preprocessing.

## Model Architecture

* Encoder: Pretrained CNN (e.g., InceptionV3) to extract feature vectors from images.
* Attention Layer: Helps the decoder focus on specific image features while generating each word.
* Decoder: An LSTM-based model that takes the image features and generates text, word by word.

## Tech Stack
* Python, TensorFlow
* NumPy, Pandas, Matplotlib, Seaborn, OpenCV

## Results
Generated captions are evaluated using BLEU scores and qualitative comparisons with ground-truth captions.
