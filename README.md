# Question Answering System (Bangla & English) using Open-Source LLM
Assessment 1 implements a Question Answering (QA) system capable of answering questions in both Bangla and English languages. The system is based on an open-source large language model (LLM) like **Llama**, fine-tuned with custom data to improve performance and accuracy for answering domain-specific or general knowledge queries.

## Features
- **Multilingual Support**: The system supports both **Bangla** and **English** languages.
- **Open-Source LLM**: Utilizes **BERT* for QA tasks.
- **Fine-Tuning**: The model has been fine-tuned on custom datasets to improve its ability to handle domain-specific queries and adapt to the data provided.
- **Web Interface**: A simple **GUI**  is provided for users to interact with the system.


### Requirements
- Python 3.8 or later
- Hugging Face Transformers library
- PyTorch 
- Flask 

# Fine-Tuning Stable Diffusion Img2Img Model for Image-to-Image Generation

Assessment 2 contains the code for fine-tuning a lightweight **Stable Diffusion Img2Img** model for **image-to-image generation** using a custom dataset, **MagicBrushDataset**. The goal is to transform source images into target-like images through training on a lightweight model, achieving high-quality results with faster training and inference times.

## Features
- Fine-tuned **Stable Diffusion Img2Img** model for image-to-image translation.
- Used custom dataset: **MagicBrushDataset**.
- Fine-tuned **UNet**, **VAE**, and **Text Encoder** components for optimal transformation.
- Lightweight Stable Diffusion model used for faster training and inference.

## Requirements
- Python 3.8+
- PyTorch
- Hugging Face Transformers
- diffusers library (for Stable Diffusion model)
- CUDA 


