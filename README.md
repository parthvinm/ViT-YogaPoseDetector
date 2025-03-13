# ViT-YogaPoseDetector

A Vision Transformer-based Yoga Pose Detection model leveraging deep learning to classify yoga postures with high accuracy.

## About

This project utilizes a **Vision Transformer (ViT)** model for pose classification in yoga practice. Unlike CNN-based approaches, ViTs effectively capture long-range dependencies in images, making them suitable for structured pose recognition. The model processes input images, extracts key pose features, and classifies them into predefined yoga postures.

## Data

The dataset used for training and evaluation is sourced from **Roboflow's Yoga Pose Computer Vision Project**. It contains a variety of labeled yoga pose images, which are preprocessed and fed into the ViT model for training.

Dataset Source Link: [Roboflow Yoga Pose Dataset](https://universe.roboflow.com/new-workspace-mujgg/yoga-pose)

## Features
- Utilizes **Vision Transformer (ViT)** for pose classification.
- Pretrained **transformer-based model** fine-tuned on yoga poses.
- Works on both **real-time webcam input** and **static images**.
- Provides pose accuracy feedback to users.

## Contributing
Contributions are welcome! If you have ideas to improve accuracy, add more poses, or optimize real-time performance, feel free to fork the repo and submit a pull request.

## Support
If you find this project helpful, consider giving it a ⭐ !

## Acknowledgments
- Hugging Face Transformers
- PyTorch Deep Learning Framework
- Roboflow Yoga Pose Dataset
