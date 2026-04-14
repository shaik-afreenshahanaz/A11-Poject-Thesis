# Text to Image Generation

# Authors 
 - Shaik Afreen Shahanaz (Y22ACS554)
 - V Nagarjuna (Y22ACS588)
 - P Mounika (Y22ACS535)
 - P Varshitha (Y22ACS536)

# Implementation
**[GitHub Repository]** : https://github.com/shaik-afreenshahanaz/Text-to-Image-Generation.git

# Overview
This project presents a **Text-to-Image Generation System** using deep learning.

The system uses **Stable Diffusion XL Turbo** to generate high-quality images from textual descriptions.
Unlike traditional graphics design, this approach automatically creates images based on user prompts using AI.

The system ensures:
  - Fast image generation
  - High-quality visual output
  - User-friendly interface
  - Real-time results

# Key Features
 - Text-to-Image Generation
 - AI-powered Image Synthesis
 - Ultra-fast Generation (4-step inference)
 - Interactive Web Interface using Gradio
 - GPU Acceleration Support
 - Custom UI Styling with CSS

# System Architect 
The system follows this pipeline:

**1. User Input**
User enters a text prompt

**2. Model Processing**
AI model interprets text and generates latent representation

**3. Image Generation**
Model converts representation into an image

**4. Output Display**
Generated image is shown in UI with generation time

# Tech Stack
  - Python
  - PyTorch
  - Diffusers Library
  - Gradio
  - PIL (Python Imaging Library)
  - CSS (for UI styling)

# Model details
 - Model Type: Text-to-Image Diffusion Model
 - Model Used: Stable Diffusion XL Turbo
 - Inference Steps: 4 (optimized for speed)
 - Guidance Scale: 0.0 (creative generation)
 - Device: GPU (CUDA) / CPU

# How to Run

python main.py

# Output
 - User provides a text description (prompt) of the image
 - The system generates an image based on the given prompt
 - Displays the generated image in the interface
 - Shows the image generation time

# Results 
 - High-speed image generation (~1–2 seconds)
 - Visually rich and creative outputs
 - Smooth UI interaction
 - Efficient performance with GPU

# Future Scope
 - Improve image quality with more inference steps
 - Add image editing features
 - Deploy as web application
 - Add prompt suggestions using NLP
 - Support batch image generation

