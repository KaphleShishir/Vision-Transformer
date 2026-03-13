# Vision-Transformer
Vision Transformer (ViT) from Scratch

This project implements a Vision Transformer from scratch using PyTorch and trains it on the MNIST dataset.

Instead of using convolutional layers like traditional CNNs, the image is first split into small patches. Each patch is converted into an embedding vector, positional information is added, and the sequence of patches is passed through multiple transformer encoder layers with self-attention. A special classification token (CLS) gathers information from all patches and is used to predict the final digit class.

The model includes patch embedding, positional encoding, multi-head self-attention, and a small MLP classification head. The implementation achieves ~97% test accuracy on MNIST, demonstrating how transformers can be applied to vision tasks even with a compact architecture.
