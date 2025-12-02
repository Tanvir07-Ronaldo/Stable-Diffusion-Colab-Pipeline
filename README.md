# 🎨 Stable Diffusion Quickstart

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/Stable-Diffusion-Quickstart/blob/main/stable_diffusion.ipynb)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97-Hugging%20Face-orange)](https://huggingface.co/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)

A streamlined Python pipeline for generating AI images from text prompts using the **CompVis/stable-diffusion-v1-4** model. This notebook is optimized to run on Google Colab using the Hugging Face `diffusers` library.

## 🚀 Features
* **Easy Setup:** Installs all dependencies (`transformers`, `diffusers`, `accelerate`) automatically.
* **GPU Optimized:** Configured to use CUDA for fast generation.
* **Authentication:** Secure login integration with Hugging Face.
* **Visualization:** Displays and saves generated images directly in the notebook.

## 📋 Requirements
* Python 3.7+
* A Google Account (for Colab)
* A Hugging Face Account & Access Token

## 🛠️ How to Run
1.  Click the **"Open in Colab"** badge above.
2.  Run the first cell to install dependencies.
3.  Enter your Hugging Face Token when prompted (see the guide below).
4.  Modify the `prompt` variable to whatever you want to visualize (e.g., "An astronaut riding a horse on Mars").
5.  Run the cell to generate and save your image!

---

## 🔑 Guide: How to Get a Hugging Face Token
To use the Stable Diffusion models, you must authenticate with Hugging Face. Follow these steps:

### 1. Create an Account
Go to [Hugging Face](https://huggingface.co/join) and sign up for a free account if you haven't already.

### 2. Generate an Access Token
1.  Click on your profile picture in the top right corner and select **Settings**.
2.  In the left sidebar, click on **Access Tokens**.
3.  Click the **Create new token** button.
4.  **Token Name:** Give it a name (e.g., "Colab-Project").
5.  **Token Type:** Select **Read** (this is sufficient for generating images).
6.  Click **Create token**.

### 3. Use the Token
1.  Copy the token string (it starts with `hf_...`).
2.  Paste it into the login cell in the notebook when asked.

---

## 📦 Dependencies
The project relies on the following libraries:
```txt
diffusers
transformers
accelerate
scipy
ftfy
