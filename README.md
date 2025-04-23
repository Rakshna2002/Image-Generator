![image](https://github.com/user-attachments/assets/f316f11e-4bc5-42ef-84ac-3750d09e0ca8)# AI Image Generator with Stable Diffusion

This is a simple and fun project where I explored how to generate images using AI — specifically, the **Stable Diffusion 2** model from Hugging Face. You just give it a prompt and it creates an image based on that.

---

## What It Does

- Takes a short text prompt and turns it into an image using AI.
- Uses the Stable Diffusion model via Hugging Face’s `diffusers` library.
- Can run on GPU (CUDA) for faster generation.
- You can tweak how the image is generated — like how detailed it should be, what size, and more.

---

## 🛠️ How It Works

- First, I set up the config: device (`cuda`), seed for consistent results, model IDs, image size, etc.
- Then I load the image generation model (`stabilityai/stable-diffusion-2`) with a few settings to speed things up and make it run on GPU.
- The `generate_image()` function is where the magic happens — you pass in a prompt, and it gives you back an AI-generated image.
- That’s pretty much it! You can plug in any text and get cool visuals back.

---

## Demo

Prompt 1:
![image](https://github.com/user-attachments/assets/fad79181-08d0-4b34-a7d7-3a3ea4955f1d)

Prompt 2:
![image](https://github.com/user-attachments/assets/f1be61cf-bc87-4bc9-afa8-4550a07e1d18)

Prompt 3:
![image](https://github.com/user-attachments/assets/c0b45d02-6945-4375-8366-4d6ebe81c735)

