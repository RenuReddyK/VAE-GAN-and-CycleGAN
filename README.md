# VAE-GAN-and-CycleGAN

## VAE:
Implemented a Variational Autoencoder (VAE) on the Fashion MNIST dataset involving training a neural network architecture to learn a probabilistic mapping of input images to a latent space. 
<p align="center">

Original Image | Reconstructed Image 
--- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/5f676a68-d718-4a6c-a5bd-72b0d58296d3") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/0b5bd2f9-af69-4f5a-9b51-dde66833ee32)
 </p>

## GAN:
Constructed from scratch following the research paper on GAN, on the STL-10 dataset. It is a powerful unsupervised learning model that facilitates domain adaptation by mapping images from one domain to another without paired training data, showcasing impressive results generating realistic images. The objective function is a min-max game, aiming to minimize the generator's loss while maximizing the discriminator's loss. Implemented tricks to address potential issues such as mode collapse, including normalization, Tanh activation in the generator's last layer, Gaussian distribution for latent code, and modified loss function.
<p align="center">
 
GAN Generated Images at epoch 15 | GAN Generated Images at epoch 30 | GAN Generated Images at epoch 45 
--- | --- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/6f007a68-e2d3-474d-9b39-48c8c9ded937") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/3178bf31-c701-41b9-a06a-c98b7659853d) | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/598220f9-78d8-4d05-9e84-c16388da55f0) 

GAN Generated Images at epoch 60 | GAN Generated Images at epoch 75 | GAN Generated Images at epoch 90
--- | --- | ---
![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/599806fc-d728-4770-9baf-60867fce4840") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/69f84535-d990-4b1b-89f6-2be56867d959) | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/b2eed21c-a27f-41f0-a10b-22dc7a3c1c1c)

</p>

## CycleGAN:
Implemented CycleGAN for image-to-image translation without paired training images. Used Edges2shoes dataset. Network architecture follows the research paper, featuring an encoder-decoder structure with convolution, instance normalization, and residual blocks. Reflection padding is applied to reduce artifacts. The objective includes adversarial loss for distinguishing generated images and cycle consistency losses to ensure mapping consistency. Training involves two generators (G: X → Y, F: Y → X) and discriminators (DY, DX). Code was developed from scratch, adhering to the specified architecture and methodology outlined in the paper.

