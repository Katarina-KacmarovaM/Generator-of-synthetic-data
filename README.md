# Synthetic Medicine Data Generator

This project provides a tool for generating synthetic telemedicine session data using different large language models and output formats (JSON, CSV, Markdown). The data is generated via a user-friendly interface built with Gradio, making it easy to experiment with different parameters and models.

## Features

- Generate synthetic telemedicine session data with realistic structure.
- Choose between different large language models (e.g., Llama, Qwen) for data generation.
- Select the desired output format: JSON, CSV, or Markdown.
- Specify the number of records to generate.
- Easy-to-use web interface powered by Gradio.
- You can edit prompts and change business application of your interest

## Getting Started

### Prerequisites

- Google Colab environment or a Python environment with GPU support (recommended for larger models).
- Hugging Face API token (required for accessing models). Store this in your Colab secrets or environment variables named `HF_TOKEN`.

### Installation

The necessary libraries are installed directly within the Colab notebook using `pip`.

```bash
!pip install -q --upgrade torch==2.5.1+cu124 torchvision==0.20.1+cu124 torchaudio==2.5.1+cu124 --index-url https://download.pytorch.org/whl/cu124
!pip install -q requests bitsandbytes==0.46.0 transformers==4.48.3 accelerate==1.3.0 openai
!pip install torch==2.3.0 torchvision==0.18.0 --upgrade --quiet
!pip install --upgrade transformers accelerate safetensors --quiet
!pip install -q gradio

```
------------------------
### If you have ideas how to improve my code  please reach out to me. I would be grateful.
###  Have fun coding !
