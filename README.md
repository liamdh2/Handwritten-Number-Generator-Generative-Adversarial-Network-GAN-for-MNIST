## 📁 Generative Adversarial Network (GAN) for MNIST

### 🧠 Overview

This project implements a **basic GAN** in **PyTorch** to generate synthetic digit images resembling the **MNIST** dataset. It demonstrates adversarial training between a generator and a discriminator.

### 🚀 Features

- **Generator & Discriminator**: Simple feedforward networks for image synthesis and classification.
- **Adversarial Training Loop**: Alternating optimization of both networks using Binary Cross-Entropy loss.
- **Progressive Visualization**: Saves generated images at intervals to track training quality.
- **GPU Compatibility**: Automatically uses CUDA if available.

### 🧰 Tech Stack

- **Language**: Python 3.8+
- **Deep Learning**: PyTorch
- **Dataset & Transforms**: torchvision (MNIST)
- **Visualization**: Matplotlib

### ⚙️ Installation & Usage

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/gan-mnist-pytorch.git
   cd gan-mnist-pytorch
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run training**:
   ```bash
   python train_gan.py --epochs 100 --batch-size 128 --latent-dim 100
   ```
4. **Generate samples**:
   ```bash
   python sample.py --checkpoint checkpoints/gan_epoch_100.pth
   ```

### 🔍 Results

- Check `samples/` folder for a grid of generated digits over training epochs.

---

### 📫 Contact

Liam - [liamharding@rocketmail.com](mailto\:liamharding@rocketmail.com)
