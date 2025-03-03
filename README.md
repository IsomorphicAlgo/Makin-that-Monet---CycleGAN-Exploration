# Makin' That Monet: GAN-Based Monet Style Transfer

## Project Overview
This project implements a Generative Adversarial Network (GAN) to create images in the style of Claude Monet's paintings. The GAN consists of two competing neural networks:
- A Generator that creates Monet-style images
- A Discriminator that tries to distinguish between real Monet paintings and generated images

## Project Goal
The main objective is to develop a GAN capable of generating 7,000 to 10,000 high-quality images in Monet's distinctive artistic style. The generator and discriminator work antagonistically, with the generator attempting to create increasingly convincing Monet-style images while the discriminator works to differentiate between authentic and generated artwork.

## Dataset Description
The project utilizes two primary datasets:

### Monet Paintings
- Number of Images: 300
- Image Dimensions: 256x256 pixels
- Format: TFRecord
- Content: Original Claude Monet paintings representing the target artistic style

### Photo Dataset
- Number of Images: 300
- Image Dimensions: 256x256 pixels
- Format: TFRecord
- Content: Real-world photographs for style transfer

## Technical Requirements
- Python 3.x
- TensorFlow
- Additional requirements will be listed in `requirements.txt`

## Project Structure
```
.
├── README.md
├── Week_5_Makin_that_Monet.ipynb   # Main project notebook
└── [Additional project files]
```

## Getting Started
1. Clone this repository
2. Install the required dependencies
3. Open and run the Jupyter notebook `Week_5_Makin_that_Monet.ipynb`

## Implementation Details
The project implements a GAN architecture where:
- The Generator network learns to transform regular photographs into Monet-style paintings
- The Discriminator network learns to distinguish between real Monet paintings and generated images
- Both networks improve through adversarial training


## Acknowledgments
- Based on the "I'm something of a painter myself" Kaggle competition
- Inspired by the works of Claude Monet 