# Image Caption Generation in Nepali

This project generates captions in Nepali for images using a CNN-LSTM model. The backend is built with FastAPI, and the frontend uses React for uploading images and displaying the resulting captions. The Flickr8k dataset has been used for training the model.


## Introduction

This project aims to generate captions in Nepali for given images. The model architecture is based on Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The backend server is implemented using FastAPI, while the frontend is developed with React to provide a user-friendly interface for image uploads and displaying captions.

## Features

- Image caption generation in Nepali.
- Simple and intuitive web interface for uploading images.
- Backend server using FastAPI.
- Efficient CNN-LSTM model for caption generation.
- Utilizes the Flickr8k dataset for training.


## Architecture

1. **Frontend**: Built with React to handle image uploads and display captions.
2. **Backend**: FastAPI server to handle requests and generate captions using the model.
3. **Model**: CNN-LSTM model trained on the Flickr8k dataset.

## Dataset

The Flickr8k dataset is used for training the model. It contains 8,000 images, each with 5 different captions.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/KRITIKA1232/ImageCaptioningSystem.git
   cd ImageCaptioningSystem
