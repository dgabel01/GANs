# GAN Models Collection

This repository contains a set of Generative Adversarial Network (GAN) models for image generation, trained or fine-tuned on different datasets, implemented for a master's thesis.

##  Contents

### 1. **Conditional GAN (cGAN)** – *128×128, UTKFace*  
- **Condition**: Age groups  
- **Dataset**: [UTKFace](https://susanqq.github.io/UTKFace/)  
- Generates human faces conditioned on specified age categories.

### 2. **DCGAN** – *64×64, CelebA*  
- **Dataset**: [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  
- Trained for general face generation.

### 3. **Pretrained StyleGAN2 & StyleGAN3**  
- **Source**: Official NVIDIA pretrained weights  
- Supports transfer learning or high-quality unconditional face generation.
