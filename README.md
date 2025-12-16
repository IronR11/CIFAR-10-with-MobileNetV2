# CIFAR-10 Image Classification using MobileNetV2

This project implements image classification on the CIFAR-10 dataset using
transfer learning with MobileNetV2 in TensorFlow/Keras.

## Features
- Transfer learning with ImageNet weights
- Two-phase training (freeze + fine-tune)
- Model checkpointing
- Clean project structure for production use

## Project Structure

src/        -> training code (.py)
notebooks/ -> experiments (.ipynb)
models/    -> model info (no weights)
data/      -> dataset info


## How to Run

1. Create virtual environment
```bash
python -m venv venv

2. venv\Scripts\activate  

3. pip install -r requirements.txt

4. python src/mark_3_classification_1_cifar_10.py






