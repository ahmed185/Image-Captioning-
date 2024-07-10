# Image-Captioning-

This repository contains an image captioning model built using PyTorch and trained on the Flickr8k dataset. The project aims to generate descriptive captions for images by combining convolutional and recurrent neural networks.
Download the dataset used: https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb Then set images folder, captions.txt inside a folder Flickr8k.

train.py: For training the network

get_loader.py: Loading the data, creating vocabulary

model.py: creating the encoderCNN, decoderRNN and connecting them togethor

utils.py: Load model, save model, printing few test cases downloaded online
