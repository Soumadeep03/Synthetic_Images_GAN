# Generating Synthetic Images Using PyTorch and Deep Convolution Generative Adversarial Networks(DCGAN)

## Overview
PyTorch is a machine learning framework that accelerates the path from research prototyping to production deployment.
The programming language used is python.The Generative Adversarial Network or GAN algorithm is created using PyTorch.
GAN is an algorithm which uses two Neural Networks(NN) which work simultaneously to improve the output of the other one with each epoch.
It contains two Neural Networks namely the Generator and Discriminator Networks.The Generator takes random noise as input and gives newly generated images.This newly generated image and images from the real dataset are given to the Discriminator and it's work is to discriminate wether the image coming as input is an real image from the dataset or a fake image generated from the generator.If it can guess correctly that image is generated then the generator improves it's output in the next epoch and if the discriminator cannot differentiate correctly then the generator has succesfully created realistic fake images.Here PyTorch is used to create the Generator and Discriminator Networks and training the model.The dataset used has 60000 images of handwritten digits.
The model is fed the dataset of images from which it generates new synthetic images.One can tune the model for better accuracy by changing the number of epochs and also view the generation of image from noise and its development with each epoch.**Can also use Tensorflow instead of Pytorch**

## Components
* Modules Imported- PyTorch, numpy and matplotlib for plotting the images in graphs.
- Configurations- Runtime set to GPU and epoch, learning rate, batch size, beta values defined.
- Dataset Loading and Processing- Dataset is loaded and divided into batches each containing 128 images.
- Discriminator- Creating a three layer discriminator network.
- Generator- Creating the generator network.
- Loss Function and Load Optimizer- Creatning the loss function and optimizing the generator and discriminator networks with Adam Optimizer
- Training Loop- Running the training loop and training the model
## Installation
This project has the following dependencies:
* Numpy `!pip install numpy`
- PyTorch `!pip install torch`
## Prerequisites
* PyTorch and basic understanding of Neural Networks
- Python
- Jupyter Notebooks
## Usefull Links
* [PyTorch](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
- [Python](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
- [TensorFlow (For those curious people)](https://www.datacamp.com/tutorial/tensorflow-tutorial)
