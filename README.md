# Text-to-Image Generation using Stable Diffusion  

This repository contains a **Jupyter Notebook** for generating high-quality images from text prompts using **Stable Diffusion**. The project utilizes **Hugging Face's `diffusers` library** and supports parameter tuning to control the output.

## Features  
- **Stable Diffusion model loading** (`dreamlike-art/dreamlike-diffusion-1.0` or `stabilityai/stable-diffusion-xl-base-1.0`)
- **Customizable text-to-image generation**
- **Parameter tuning:**
  - `num_inference_steps` (controls detail & quality)
  - `height` & `width` (image resolution)
  - `num_images_per_prompt` (generates multiple variations)
  - `negative_prompt` (filters out unwanted elements)
- **GPU acceleration with `torch.cuda` support**

