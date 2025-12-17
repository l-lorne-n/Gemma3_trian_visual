# Fruit Counting with Vision-Language Models for UAV Perception

This project explores fruit counting and visual reasoning using lightweight
vision-language models, with a focus on deployment in UAV (drone) perception
scenarios.

The project is designed to balance model capability and computational efficiency,
making it suitable for both local machines and micro/edge devices.


## Model and Training

- Base Model: **Gemma 3 Vision-Language Model**
- Frameworks: PyTorch, HuggingFace Transformers
- Quantization: 4-bit (via Unsloth) for reduced memory footprint
- Training Objective: Visual input → numerical count inference

The training and experiments are conducted using Kaggle GPU (T4 GPU) environments and
are designed to remain compatible with local execution on consumer-grade GPUs
or compact computing platforms.


## Dataset

This project uses a custom fruit image dataset curated by the author.

- Platform: Kaggle Datasets  
- License: Apache License 2.0  
- Size: 967 images

Dataset URL:  
https://www.kaggle.com/datasets/langningyan/ffruit2-data

The dataset is publicly available and therefore not included in this repository.


