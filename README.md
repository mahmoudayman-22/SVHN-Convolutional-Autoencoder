# SVHN Convolutional Autoencoder

An unsupervised deep learning project focused on building and evaluating a **Convolutional Autoencoder (CAE)** for dimensionality reduction and representation learning on the **Street View House Numbers (SVHN)** dataset using **PyTorch**.

---

##  Project Overview
This project explores unsupervised representation learning by compressing RGB house number images into a low-dimensional latent space and reconstructing the original images. The primary objective is to analyze the trade-off between latent space dimensionality, reconstruction fidelity, and spatial information preservation.

---

##  Key Features
- **Encoder-Decoder Architecture:** Designed a fully convolutional encoder to compress input RGB images ($32 \times 32 \times 3$) into compact latent representations, paired with a transposed convolutional decoder to reconstruct the original inputs.
- **Latent Dimension Experiments:** Conducted comparative analysis between different latent vector sizes (e.g., **64 vs. 16 dimensions**) to evaluate information bottleneck dynamics.
- **Performance Evaluation:** Evaluated reconstruction quality using **Mean Squared Error (MSE) loss**, visual reconstruction fidelity, and feature preservation across training epochs.

---

##  Tech Stack & Tools
- **Framework:** PyTorch
- **Core Libraries:** NumPy, Matplotlib, Torchvision
- **Dataset:** SVHN (Street View House Numbers)
- **Language:** Python

---

##  Results & Observations
- **Reconstruction Fidelity:** Higher latent dimensions (e.g., 64) preserved sharp edges and digit color variations effectively, whereas lower dimensions (e.g., 16) learned smoother, higher-level abstract features.
- **Loss Convergence:** Both architectures demonstrated steady MSE loss reduction, confirming effective reconstruction capabilities without severe information loss.

---

##  Author
**Mahmoud Ayman Zaki**
- **Email:** mahmoudayman340@gmail.com
- **GitHub:** [@mahmoudayman-22](https://github.com/mahmoudayman-22)
