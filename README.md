# Retinal Optical Coherence Tomography (OCT) Classification Using CNN

## Overview
This project implements a Convolutional Neural Network (CNN) for classifying retinal OCT images. The model is trained using VGG16 and AlexNet architectures to identify different retinal conditions. OCT imaging is widely used in ophthalmology to detect diseases such as macular degeneration and diabetic retinopathy.

## Dataset
The dataset used for this project consists of high-resolution cross-sectional images of the retina. The images are labeled based on different retinal conditions. The dataset undergoes preprocessing, including resizing, normalization, and augmentation to improve model performance.

## Model Architecture
- **VGG16:** A deep CNN architecture known for its simple yet effective design.
- **AlexNet:** A pioneering deep learning model known for its efficiency in image classification.

## Dependencies
Ensure you have the following dependencies installed:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

## Usage
Clone the repository:

```bash
git clone https://github.com/your-username/oct-classification-cnn.git
cd oct-classification-cnn
```

Run the training script:

```bash
python train.py
```

Evaluate the model:

```bash
python evaluate.py
```

## Results
The trained model achieves high accuracy in classifying OCT images, demonstrating the effectiveness of deep learning in medical imaging.
