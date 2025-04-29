# BLIP-2-Fine-Tuned-for-Image-Captioning-with-the-Flickr8k-Dataset

# 🖼️ BLIP-2 Fine-Tuned for Image Captioning (Flickr8k)

This repository contains a complete notebook for fine-tuning the BLIP-2 model on the [Flickr8k dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k) to generate descriptive captions for images. It leverages Hugging Face's `transformers`, the `peft` library for parameter-efficient fine-tuning (LoRA), and `datasets` for data handling.

## 🚀 Features

- 📦 Uses BLIP-2 vision-language model from Hugging Face
- 🖼️ Prepares and loads Flickr8k dataset with images and captions
- 🔧 Applies LoRA (Low-Rank Adaptation) via PEFT for lightweight fine-tuning
- 🧠 Supports training and inference directly in the notebook
- ✅ Great for beginners and researchers experimenting with image captioning

## 🛠️ Dependencies

- `transformers`
- `datasets`
- `peft`
- `bitsandbytes`
- `torch`
- `Pillow`, `matplotlib`, `pandas`

