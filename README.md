# ImageCaptioning

This project implements an image captioning system that generates descriptive captions for input images. It utilizes a pretrained Convolutional Neural Network (CNN) to extract image features and a Transformer-based decoder to generate natural language descriptions.

## Features

- **Pretrained CNN Encoder**: Extracts rich feature representations from input images.
- **Transformer Decoder**: Generates coherent and contextually relevant captions based on image features.
- **Jupyter Notebook Implementation**: Provides an interactive environment for experimentation and visualization.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/lehau007/ImageCaptioning.git
   cd ImageCaptioning
   ```

2. **Set Up a Virtual Environment** (Optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   If you do not have some libs, environment => intalls follow errors 

## Usage

1. **Open the Jupyter Notebook**:

   ```bash
   jupyter notebook pokemon-image-captioning.ipynb
   ```

2. **Run the Notebook Cells**:
   - In this repo, there are not datasets, so if you want to reapply => add datasets and replace relevant code. 

   - Follow the instructions within the notebook to load the model, preprocess images, and generate captions.
   - You can experiment with different images to see how the model performs.

## Dataset

The notebook may reference a specific dataset for training or evaluation. Ensure you have access to the dataset and adjust the paths in the notebook accordingly.

## Model Architecture

- **Encoder**: A pretrained CNN (e.g., ResNet, Inception, VGG16) that processes input images to extract feature vectors.
- **Decoder**: A Transformer-based model that takes the image features and generates corresponding captions in natural language.

## Results

Sample outputs and performance metrics can be found within the Jupyter notebook. The model demonstrates the ability to generate contextually relevant captions for various images.

## References
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## Acknowledgments

Thanks to the authors of the referenced papers and the open-source community for their valuable contributions.
