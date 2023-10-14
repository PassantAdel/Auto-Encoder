# Autoencoder for Image Reconstruction

This repository contains code that demonstrates the implementation of an autoencoder using TensorFlow and Keras for image reconstruction. The script focuses on encoding and decoding images, along with the addition of noise for robustness training.

## Requirements
To run the script, you need to have the following dependencies installed:

- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the required packages using pip:

## Installation
1. Clone the repository: `git clone https://github.com/PassantAdel/Auto-Encoder.git` 
2. Install the required packages: `pip install -r requirements.txt`

## Usage
1. Run the script in a Python environment or Jupyter Notebook.
2. View the generated visualizations and reconstructed images.

## Results
The autoencoder achieves a reconstruction loss of 0.0078 after 10 epochs.

## Description
The script performs the following operations:

* Loads image data using the Keras ImageDataGenerator.
* Constructs an autoencoder architecture using TensorFlow and Keras.
* Adds random noise to the input images for training.
* Encodes images to a compressed representation using the encoder.
* Decodes the encoded representation back to the original images using the decoder.
