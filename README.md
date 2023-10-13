# Fashion GANs

## Overview

This project implements a Generative Adversarial Network (GAN) to generate fashion item images using the MNIST dataset. GANs are a class of deep learning models that can generate data samples that resemble a given dataset. In this case, we aim to generate realistic images of various fashion items such as shoes, shirts, and dresses.

A Fashion GAN project typically consists of several key components. The generator, one of the neural networks in the GAN, takes random noise as input and endeavors to create lifelike fashion images, encompassing clothing items, accessories, or complete outfits. In contrast, the discriminator, the second neural network, assesses whether the generator's output is authentic or counterfeit by comparing it to real images from a dataset. To facilitate this learning process, a substantial dataset of genuine fashion images is essential, as it serves as the generator's reference for understanding authentic styles and features. The project relies on a loss function to quantify the disparity between the generator's creations and real images, with the aim of minimizing this loss during training to encourage the generation of increasingly realistic fashion items. The training itself involves an adversarial interplay, as the generator strives to deceive the discriminator with its outputs, while the discriminator aims to improve its ability to distinguish genuine from synthetic images, ultimately culminating in the generation of high-quality fashion visuals.

## Dataset

The MNIST dataset is a collection of 28x28 grayscale images of handwritten digits from 0 to 9. For this project, we repurpose this dataset to represent fashion items, mapping each class of fashion item to a digit. The dataset consists of the following classes:
- 0: T-shirt/top
- 1: Trouser
- 2: Pullover
- 3: Dress
- 4: Coat
- 5: Sandal
- 6: Shirt
- 7: Sneaker
- 8: Bag
- 9: Ankle boot
![epoch_1000_output](https://github.com/ghananjani/FashionFusion-Creating-Styles-with-GANs/assets/88573690/4011cee5-4fe1-4e8d-a591-cf239b4b6292)

## Dependencies

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib (for visualization)
