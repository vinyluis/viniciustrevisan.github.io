---
type: portfolio
title: GANs for sketch-to-image translation and image synthesis
subtitle: Master's degree dissertation
layout: default
modal-id: 2
date: 2022-11-30
thumbnail: dissertation_thumb_400_289.png
img: dissertation.png
alt: GANs for sketch-to-image translation and image synthesis

project-date: 2020 - 2022
category: Computer Vision

link_text: PDF [PT-BR]
link_url: content/portfolio/assets/Estudo sobre o uso de redes adversárias generativas para transformação de contornos em imagens e síntese de imagens.pdf

github_url:

summary: I studied the use of deep learning and generative adversaial networks (GANs) in tasks related to computer vision, image processing, and computer graphics. The topic of my dissertation was "A study about the use of generative adversarial networks for image contour transformation and image synthesis."

---

### Estudo Sobre o Uso de Redes Adversárias Generativas para Transformação de Contornos em Imagens e Síntese de Imagens

***A study about the use of generative adversarial networks for image contour transformation and image synthesis***

As part of the studies for my master's degree, I tested many GANs in different applications. I was limited by computational resources, so I could not experiment with state-of-the-art models such as StyleGANs trained from scratch.

On the first part of the work I studied using Pix2Pix and CycleGAN in sketch-to-image aplications. The framework is available on the corresponding [Github Repository](https://github.com/vinyluis/Pix2Pix-CycleGAN).

The second part is a proposal of an autoencoder generator to quickly manipulate and edit images. The experiments were made with many combinations of components (generator, discriminator, loss, mapping networks, etc.) and serves as a guide for future projects. The code is also available on [Github](https://github.com/vinyluis/Autoencoders).

All the studies and results are on [my dissertation](http://biblioteca.ufabc.edu.br/index.php?codigo_sophia=124594) (in Portuguese).

---

### Abstract
*Significant advances in image processing, computer vision, and computer graphics applications were recently achieved, much due to techniques based on Generative Adversarial Networks (GANs). Among those applications we can cite super resolution, image to image translation, style transfer, picture restoration and image synthesis. In this work we study the use of GANs in contour-to-image translation and face image synthesis applications.*

*The first task involves transforming car sketches into realistic images, and cartoon sketches into a colorized and texturized version. We analyze and discuss the use of both Pix2Pix and CycleGAN architectures in this task, performing experiments with different parameters and configurations to enhance the quality of the synthetic image.*

*In the synthesis application, inspired by image manipulation works, we explore how to generate synthetic images of human faces using conditional GANs as autoencoders, so that they can generate latent vectors that allow image manipulation directly on the feature latent space. We tested many combinations of different generators, discriminators, loss functions and training techniques to understand which elements contribute to generate better images.*

### Results

Here are some results presented on the dissertation.

#### Sketch-to-image

![Sketch-to-image results](content/portfolio/images/dissertation_results_sketch.png)

#### Autoencoders

![Autoencoder results](content/portfolio/images/dissertation_results_autoencoders.png)