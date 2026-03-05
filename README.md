# Diffusion Practise

Implemented diffusion from scratch for learning and experimentation.

## How to run

1. Run the diffusion implementation:
   ```bash
   python StableDiffusion/main.py
   ```
   You can also run related experiments from `VAE/main.py` and `VQ-VAE/main.py`.

## Limitations

- Model channels are downsized to fit within 8 GB VRAM.
- Due to this reduced capacity, image generation quality is currently not good.