# Art-Generation-with-neural-style-transfer
An implementation of Neural Style Transfer (NST) using TensorFlow and VGG19. Generate artistic images by blending the content of one image with the style of another.
# 🎨 Deep Learning & Art: Neural Style Transfer

This project implements **Neural Style Transfer (NST)** using **TensorFlow** and a **pre-trained VGG19 model**.  
The goal is to **generate new artistic images** by combining the **content** of one image with the **style** of another.

---

## 🚀 Project Overview

Neural Style Transfer is an algorithm developed by **Gatys et al. (2015)**.  
It uses a **pre-trained Convolutional Neural Network (CNN)** to extract content and style representations from images and then optimizes a **generated image** to minimize both **content cost** and **style cost**.

**Key Highlights:**
- Implemented a **content cost function** to preserve image structure.
- Designed a **style cost function** using Gram matrices.
- Combined both costs into a **total loss** function.
- Trained a model to generate an artistic image by blending **content** and **style**.
- Used **VGG19** as the feature extractor for transfer learning.

---



