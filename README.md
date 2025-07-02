This repository features a collection of Stable Diffusion models designed for high-quality text-to-image generation. These models are built on latent diffusion techniques and trained from scratch for improved performance and flexibility. The repo includes support for various generation modes like classic text-to-image, depth-guided synthesis, inpainting, and upscaling.

🔍 Highlights:
Stable Diffusion v2.0 and v2.1 models (512x512 and 768x768 resolutions)

Text-to-Image, Img2Img, Inpainting, and Super-resolution capabilities

UnCLIP models for enhanced creativity and image mixing

Depth2Image model for structure-preserving generation using MiDaS

Integrated support for xformers (efficient attention) and Intel PyTorch extensions for optimized CPU inference

Includes demo scripts using Gradio and Streamlit

🧰 Requirements:
Python, PyTorch, transformers, diffusers

Optional: xformers (for speed on GPU), Intel® Extension for PyTorch* (for optimized CPU runs)

⚠️ Disclaimer:
These models reflect the biases and limitations of the data they were trained on. They are research artifacts and should not be used in production without appropriate safety and ethical considerations.

