# Fast Sampling Diffusion on large quantities of images using an additional layer
Author: [Ng Zheng Jue](https://github.com/xinjue37), [Ong Ming Jie](https://github.com/ethanong98), [Ng Rui Qi](https://github.com/Ruiqi2002), [Tan Hong Guan](https://github.com/tanhg1116) 

* This is a project developed in undergraduate Year 3 - Semester 1.
* This repository consists of code to **increase the sampling speed of the latest popular neural architecture in image generation -- diffusion model**. The dataset used for experiment is the CIFAR-10 dataset.
* The repository consists
    * 3 Jupyter notebook files that contain code about how to implement an additional layer on the diffusion model to increase the sampling speed
    * (When using GeForce RTX 3080) The training of each diffusion model takes about 2 GPU hours, and the training of the additional layer takes about 1 GPU 
    * The details implementation of how it works and prove of diffusion model in math is available in [Report.pdf](https://github.com/xinjue37/Fast-Sampling-Diffusion-on-large-quantities-of-images/blob/main/Report.pdf).

## Abstract
In recent times, generative models have become a hot topic in the field of Artificial
Intelligence. Namely, there is a recent surge in interest regarding the topic of
Diffusion models, said to be able to generate images of higher quality compared to
Generative Adversarial Networks (GANs). However, a known limitation about the
diffusion models is the inferior sampling speed compared to other generative models.
Many research papers aim to improve this sampling speed by reducing the sampling
steps by modifying mathematical formulas in diffusion models. However, we have
found no research papers that modify the architecture of the diffusion models to
increase sampling speed. By adding an additional layer into the model, we aim to
discover the effects that it has on the sampling speed and quality of the images in this
paper.
