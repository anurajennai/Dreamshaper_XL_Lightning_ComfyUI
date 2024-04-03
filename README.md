# Dreamshaper_XL_Lightning_ComfyUI
Comfy UI Colab setup and workflow for Stable diffusion Dreamshaper XL Lightning Model

# Introduction
Here is the collab notebook 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/anurajennai/Dreamshaper_XL_Lightning_ComfyUI/blob/main/Dreamshaper_XL_Lightning_comfyui_colab.ipynb)

#
I have used Dreamshaper XL Lightning as the SD model. 
If you want a safe version use 
https://huggingface.co/Lykon/dreamshaper-xl-lightning/resolve/main/DreamShaperXL_Lightning-SFW.safetensors?download=true instead.

# ComfyUI
![Alt text](https://github.com/anurajennai/Dreamshaper_XL_Lightning_ComfyUI/blob/main/dreamshaper_xl_lightning_workflow.jpg?raw=true "Workflow")

Use 1024x1024 as default size
Use DPMPP_SDE as sampler and KARRAS as scheduler
Use 6 steps and CFG 2. Build negative prompts as needed.

For upscaling Real_ESRGANx2 is recommended.



