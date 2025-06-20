<h1 align="center" id="title">Generating-Realistic-Images-using-DDPM</h1>

<p align="center"><img src="https://socialify.git.ci/ajeshraj402/Generating-Realistic-Images-using-DDPM/image?custom_description=A+diffusion-based+generative+model+trained+on+CIFAR-10+to+synthesize+realistic+images%2C+compared+against+VAE+and+VAE-GAN+baselines.&amp;description=1&amp;font=Bitter&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Brick+Wall&amp;theme=Light" alt="project-image"></p>

<p id="description">This project implements a Denoising Diffusion Probabilistic Model (DDPM) to generate realistic images by learning to reverse a gradual forward noise process. The model is trained on the CIFAR-10 dataset to synthesize high-quality images from pure noise. It also includes comparisons with Variational Autoencoders (VAE) and VAE-GAN hybrid models highlighting the strengths of diffusion models in generative image synthesis.</p>

<h2>📷 Project Screenshot:</h2>

<img src="https://drive.google.com/uc?id=1aaWCh-emXdLlsPqCJoGL5j8J6U44-ehh" alt="project-screenshot" width="400">

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the Repository</p>

```
git clone https://github.com/ajeshraj402/Generating-Realistic-Images-using-DDPM.git
```

<p>2. Navigate to the folder</p>

```
cd Generating-Realistic-Images-using-DDPM
```

<p>3. Install requirements</p>

```
pip install -r requirements.txt
```

<h2>🍰 Contribution Guidelines:</h2>

Implemented the Reverse Diffusion Process: Designed and coded the reverse denoising process central to the DDPM model where a trained U-Net predicts and progressively removes noise from images. This involved integrating timestep embeddings configuring the noise prediction loss and ensuring stable reconstruction of clean images from pure Gaussian noise across 300 diffusion steps. Trained and Evaluated the DCGAN Baseline on CIFAR-10 Implemented and fine-tuned a Deep Convolutional GAN (DCGAN) using PyTorch to serve as a baseline for comparison. Focused on model stability loss behavior and output quality during training and used Fréchet Inception Distance (FID) scores to benchmark its performance against DDPM and other generative models.

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python 3.8+
*   PyTorch
*   Torchvision
*   Matplotlib
*   VS Code
*   Jupyter Notebook
