# Image Caption Generator using CNN & LSTM
[📓 Open in Google Colab](https://colab.research.google.com/drive/1aR8h4QGRpYI4OliN8HjX3DR3wkqhrYfH?usp=sharing)
## Overview
This project implements an **Image Caption Generator** using Deep Learning. The model combines **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory networks (LSTMs)** to automatically generate descriptive captions for images.

It first extracts features from images using a pre-trained CNN and then feeds these features into an LSTM network to generate natural language captions.

---

## Features
- Extracts image features using **VGG16** (pre-trained on ImageNet).  
- Cleans and preprocesses captions for training.  
- Generates captions for unseen images.  
- Evaluates model performance using **BLEU scores**.  
- Visualizes predictions alongside actual captions.

---

## Dataset
- Uses the **Flickr8k dataset** (8,000 images with 5 captions each).  
- Available on [Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k).  
- Optionally, a smaller subset can be used to reduce training time.

---

## Results
- Generates captions that closely match human annotations.
- BLEU scores indicate quality of generated captions.
- Visualize actual vs predicted captions alongside images.
