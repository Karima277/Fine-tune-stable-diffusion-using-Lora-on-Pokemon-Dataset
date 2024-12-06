# Fine-tune-stable-diffusion-using-Lora-on-Pokemon-Dataset

This project fine-tunes a Stable Diffusion model using LoRA (Low-Rank Adaptation) to generate Pokémon-style images based on text prompts. By leveraging the `CompVis/stable-diffusion-v1-4` model and a custom Pokémon-themed dataset, we created a lightweight, efficient model capable of producing highly detailed Pokémon-inspired artwork.

---

## 🎨 **Project Overview**
The goal of this project is to:
1. Fine-tune a Stable Diffusion model using LoRA for Pokémon-style image generation.
2. Efficiently adapt pre-trained weights with LoRA, enabling personalized model training without the need for extensive computational resources.
3. Generate unique Pokémon-style images from simple textual descriptions.

---

## 🚀 **Features**
- **Fine-Tuned LoRA Weights**: Efficiently fine-tuned the `UNet` and `CLIPTextEncoder` components of Stable Diffusion using the LoRA method.
- **Text-to-Image Generation**: Generates high-quality Pokémon-inspired images from prompts like "A cute electric type Pokémon in a forest."
- **Lightweight Model**: LoRA reduces the number of trainable parameters, enabling faster training and lower GPU memory usage.
- **Dataset**: Uses a Pokémon-themed dataset (`alc15492/pokemonreplica`).

---

## 🛠️ **Setup Instructions**

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- CUDA-compatible GPU (optional but recommended)
- Libraries: `torch`, `diffusers`, `transformers`, `datasets`, `peft`, `wandb`, `Pillow`

