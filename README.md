# Undergraduate-Y3S1 Fast Sampling Diffusion on large quantities of images using an additional layer
Author: Ng Zheng Jue, Ong Ming Jie, Ng Rui Qi, Tan Hong Guan 

* This is a project developed in undergraduate Year 1 - Semester 1.
* The repository consists
    * Jupyter notebook file that contains code about how to implement additional layer on diffusion model to increase the sampling speed
    * If you are interested how it implemented, you can see the **report.pdf** for details
* The data we used are CIFAR-10


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
