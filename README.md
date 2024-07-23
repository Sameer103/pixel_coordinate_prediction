# Predicting the coordination of a Single White Pixel in a 50x50 Image using Deep Learning
## Overview
This project aims to predict the coordinates (x, y) of a single white pixel (value 255) in a 50x50 grayscale image where all other pixels are black (value 0). The project involves generating a dataset, building and training a convolutional neural network (CNN), and evaluating its performance.

![predicted coordinates](https://github.com/user-attachments/assets/a20acd50-d5aa-4dd4-aee6-801a669e4d13)
<p align="center">
Predicted Coordinates with Images in the dataset
</p>  

## Installation
To run this project, you need to have Python installed. It is recommended to use a virtual environment: 

### Clone the Repository
* git clone https://github.com/Sameer103/pixel_coordinate_prediction.git
* cd pixel-coordinate-prediction
### Create a Virtual Environment 
* python -m venv venv

## Output
The Colab notebook includes plots of:

* Training and validation loss over epochs.
* Training and validation accuracy over epochs.
* Ground truth vs. predicted coordinates for sample test images.
![training dat](https://github.com/user-attachments/assets/aaba8e75-0acc-4bb1-aa5d-2c737a89eb2d)
<p align="center">
Visualizing the loss and accuracy over epochs for both training and validation sets to understand the model's learning process and check for overfitting or underfitting
</p>

Outputs shown here are subject to random dataset, this output can alter with the random dataset generated with the function.
Also the number of values can be alter with respect to the system support
