# DCGAN Implementation

This repository contains an implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic images from noise.

## Features
- Implements DCGAN with a Generator and Discriminator.
- Uses the CelebA dataset for training.
- Saves generated images after each epoch.
- Supports CUDA for faster training.

## Setup Instructions

### Prerequisites
Ensure you have Python installed along with the required dependencies:
```bash
pip install torch torchvision numpy matplotlib
```

### Dataset
Download and extract the CelebA dataset into the `data` directory.
```bash
mkdir -p data
# Place the dataset inside the `data` folder
```

### Run Training
To train the DCGAN model, run:
```bash
python dcgan.py
```

### Generate Images
Once training is complete, generate new images using:
```bash
python dcgan.py --generate
```

## Directory Structure
```
├── data/                  # Dataset directory
├── models/                # Saved models
├── results/               # Generated images
├── dcgan.py               # Main script
├── README.md              # Documentation
```

## Sample Output
Generated images will be saved in the `results/` folder after training.

## License
This project is open-source and free to use.

## Author
Rushil Shah

