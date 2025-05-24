# mnist-variational-autoencoder
A PyTorch implementation of a Variational Autoencoder trained on the MNIST dataset. The project demonstrates digit generation from random latent vectors and reconstruction of uploaded digit images using a Gradio web interface.

# VAE MNIST Digit Generator & Reconstructor

This project implements a Variational Autoencoder (VAE) in PyTorch, trained on the MNIST dataset. It features a Gradio web app for generating new digits and reconstructing uploaded digit images.

## Features
- Generate new handwritten digits from random latent vectors.
- Reconstruct any uploaded digit image (resized to 28x28).
- Interactive web demo using Gradio.

## Try it out!
- [Live Demo on Hugging Face Spaces](https://huggingface.co/spaces/your-username/vae-mnist-demo) (if deployed)
- [GitHub Repository](https://github.com/your-username/vae-mnist-demo)

## How it works
- The VAE learns a compressed latent representation of MNIST digits.
- You can generate new digits or upload your own for reconstruction.

## Technologies
- PyTorch, Gradio, torchvision, matplotlib, PIL

## Screenshots
![Generated Digits](screenshots/generated.png)
![Reconstructed Digits](screenshots/reconstructed.png)
