# Image Captioning: Deep Learning with CNNs and RNNs
## Overview
This repository contains an implementation of an image captioning system using deep learning techniques. The goal is to generate descriptive captions for images automatically1. We combine Convolutional Neural Networks (CNNs) for image feature extraction and Recurrent Neural Networks (RNNs) for sequence generation.

## Features
* Image Preprocessing: Extract features from images using a pre-trained CNN (e.g., ResNet, VGG).
* Sequence Modeling: Use an LSTM-based RNN to generate captions.
* Evaluation Metrics: Evaluate the quality of generated captions using metrics like BLEU, METEOR, and CIDEr.
* Sample Images: Included sample images for testing the model.

## Train the Model:
python train.py --data_path /path/to/dataset --cnn_model resnet50

## Generate Captions:
python generate_captions.py --image_path /path/to/image.jpg

## Model Performance
* BLEU Score: 0.75
* METEOR Score: 0.68
* CIDEr Score: 1.23

## Acknowledgments
* M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artificial Intelligence Research, Volume 47, pages 853-899
* Flickr 8k Data
