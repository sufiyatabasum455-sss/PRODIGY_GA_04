# PRODIGY_GA_04
Image-to-Image Translation using cGANs
# Task-04: Image-to-Image Translation with cGANs

## Overview

This project is part of my Generative AI Internship at Prodigy InfoTech.

The objective of this task is to implement image-to-image translation using a Conditional Generative Adversarial Network (cGAN) inspired by the Pix2Pix approach.

## About the Project

The model learns to translate an input image into a corresponding target image.

For this task, the **Facades dataset** was used. The dataset contains paired images of building facades.

The cGAN consists of two main components:

- **Generator** – Generates a translated image from the input image.
- **Discriminator** – Determines whether the generated image is similar to the real target image.

## Implementation

For this task:

- The Pix2Pix Facades dataset was downloaded.
- Paired images were separated into input and target images.
- Images were resized to 128 × 128 pixels.
- A Generator model was created using convolutional and transposed convolutional layers.
- A Discriminator model was created to distinguish real and generated images.
- The cGAN was trained for 5 epochs.
- A translated image was generated using the trained Generator.

## Technologies Used

- Python
- TensorFlow
- Keras
- Conditional GAN (cGAN)
- Pix2Pix
- Google Colab

## Files

- `Task-04_Image-to-Image_Translation_with_cGANs.ipynb` – Colab notebook containing the implementation.
- `translated_image.png` – Generated image produced by the trained cGAN.

## Dataset

**Pix2Pix Facades Dataset**

The dataset contains paired facade images used for image-to-image translation.

## Output

The generated image is available as:

`translated_image.png`

## Task

**Task-04: Image-to-Image Translation with cGANs**

Completed as part of the **Generative AI Internship at Prodigy InfoTech**.
