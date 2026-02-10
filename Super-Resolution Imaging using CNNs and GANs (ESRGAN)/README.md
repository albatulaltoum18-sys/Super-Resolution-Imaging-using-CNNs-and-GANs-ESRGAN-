Super-Resolution Imaging using CNNs and GANs (ESRGAN)

This project explores super-resolution image reconstruction using deep learning, with a focus on comparing traditional CNN-based methods and GAN-based approaches. The work highlights the effectiveness of Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN) in restoring fine details and perceptual quality from low-resolution images.

Overview
The project investigates how GAN-based models outperform conventional CNN models in single-image super-resolution tasks. While CNNs such as SRCNN provide stable and smooth results, GAN-based models like ESRGAN generate more realistic textures and sharper details, making them more suitable for real-world applications.

Methodology
The workflow includes data preprocessing, model training, and evaluation. Two models are considered:

SRCNN as a baseline CNN-based approach

ESRGAN as an advanced GAN-based approach using adversarial and perceptual loss

Both models are trained on the Urban100 dataset, and their performance is evaluated using objective metrics and visual comparison.

Dataset
The project uses the Urban100 dataset, which contains urban scene images with complex textures. The dataset is widely used in super-resolution research and is suitable for evaluating perceptual quality and texture recovery.

Results
The experimental results show that ESRGAN achieves higher PSNR and SSIM values compared to CNN-based models. Visually, ESRGAN produces sharper edges and more realistic textures, while CNN outputs tend to be smoother and less detailed.

Tools and Technologies
Python
PyTorch
ESRGAN (BasicSR framework)
Jupyter Notebook


How to Run
Open the Jupyter Notebook files and run the cells sequentially after preparing the required dataset and environment.

Purpose
This project studies and compares CNN-based and GAN-based super-resolution techniques.

Author
Albatul Altoum (team project)