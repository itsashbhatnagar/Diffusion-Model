# Diffusion Model For CIFAR-10

This repository contains a diffusion model implementation for image generation using the CIFAR-10 dataset.
The model architecture consists of a U-Net with residual blocks and time embeddings. It utilizes a forward diffusion process to gradually add noise to images and learns to reverse this process to generate images from noise.

The code is written in Python and uses TensorFlow and Keras. It includes functionality for training the model, generating images, and visualizing the diffusion process.

This project is designed to be run in a Google Colab environment, leveraging its GPU capabilities for efficient training and inference.
