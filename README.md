# AI Image Generator with Stable Diffusion

This is a simple and fun project where I explored how to generate images using AI — specifically, the **Stable Diffusion 2** model from Hugging Face. You just give it a prompt and it creates an image based on that.

---

## Image Generation Pipeline

The Stable Diffusion model generates images based on short descriptive prompts. The following configuration parameters are used:

- **Prompt**: A sentence or phrase describing the desired image (e.g., *"Protest to save water"*)
- **Model**: Pre-trained Stable Diffusion 2 (`stabilityai/stable-diffusion-2`)
- **Inference Settings**:
  - Image resolution: 400x400 px
  - Inference steps: 35
  - Guidance scale: 9
  - Generator seeded for reproducibility (`torch.Generator.manual_seed(42)`)

---

## System Modules

### 1. Prompt Handling

- Takes user prompt as input.
- Passes the prompt into the model pipeline.

### 2. Model Loading and Configuration

- Loads the Stable Diffusion model from Hugging Face.
- Configures device (`cuda`) and FP16 for fast GPU processing.

### 3. Image Generation and Postprocessing

- Generates image using the prompt.
- Resizes output for visualization.
- Displays or stores image results.

---

## Acknowledgements

This project was done as part of a creative exploration into generative AI. I’ve referred to several online tutorials, videos, and open-source repositories while building and understanding the solution:

- YouTube tutorials on image generation with Hugging Face and diffusers.
- Hugging Face documentation and model cards.
- Community blogs and GitHub repos.

---

## Demo

Prompt 1:
![image](https://github.com/user-attachments/assets/fad79181-08d0-4b34-a7d7-3a3ea4955f1d)

Prompt 2:
![image](https://github.com/user-attachments/assets/f1be61cf-bc87-4bc9-afa8-4550a07e1d18)

Prompt 3:
![image](https://github.com/user-attachments/assets/c0b45d02-6945-4375-8366-4d6ebe81c735)
