# CNN Clothing Classifier
This project uses a Convolutional Neural Network (CNN) to classify what I am wearing based on a custom dataset of images. The model is trained to identify different types of clothing items.

## Dataset
The dataset consists of images captured from various angles and lighting conditions (with a Webcam), featuring different clothing items. It includes categories like `Mic`, `Nothing`, `Mask`, and more could be more if needed.

## Model Architecture
The model is built using a Convolutional Neural Network (CNN) with layers including convolutional, pooling, and fully connected layers. The architecture is designed to capture the nuances in different clothing items.

# CNN Clothing Classifier

This project uses a Convolutional Neural Network (CNN) built with PyTorch to identify clothing items from images. The model is trained on a custom dataset of myself wearing different outfits.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview
This project is a part of my exploration into computer vision and deep learning. The goal is to create a model that can recognize what I'm wearing based on a set of images taken from various angles.

## Dataset
The dataset consists of images collected manually, categorized into different clothing items such as Mic, Nothing, and Mask. It could be much more if needed.

## Model Architecture
The CNN model was built using PyTorch with several convolutional layers, pooling layers, and fully connected layers. Dropout and data augmentation were used to prevent overfitting.

## Training
The model was trained over multiple epochs with a batch size of 32, using an Adam optimizer. The training process was documented in the provided Jupyter Notebook.

## Results
The model achieved an accuracy of 95% on the validation set. Below are some sample predictions:

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
