# Bone Fracture Detection Using Image Processing

This project focuses on automating the detection of bone fractures in X-ray images using both **image processing techniques in MATLAB** and **machine learning models**. The solution aims to improve the accuracy and speed of fracture detection, reducing reliance on manual inspection by radiologists.

## Project Overview

Bone fractures are a common injury requiring accurate and timely detection for effective treatment. Traditional manual inspection of X-ray images by radiologists can be time-consuming and error-prone, especially in subtle or complex cases. This project introduces two approaches to overcome these limitations:
1. **MATLAB-Based Image Processing**: Edge detection, contrast enhancement, and Hough Transform to detect fractures.
2. **Machine Learning-Based Approach**: Using convolutional neural networks (CNNs) for automated classification of X-ray images.

## Key Features

- **MATLAB Implementation**:
  - Noise reduction using Gaussian and median filters.
  - Edge detection using the Canny algorithm.
  - Fracture identification through Hough Transform analysis.

- **Machine Learning Implementation**:
  - Training a CNN using TensorFlow/PyTorch for fracture classification.
  - Preprocessing steps including data augmentation and normalization.
  - Evaluation metrics: Accuracy, Precision, Recall, and F1-score.

## Results

- **MATLAB-based approach** effectively highlights fracture lines but struggles with subtle fractures.
- **CNN-based approach** provides high accuracy and robustness, outperforming traditional methods.

## Future Scope

- Enhancements to image processing algorithms for improved detection.
- Collection of larger, more diverse datasets for better machine learning performance.
- Real-time deployment for clinical use.

## Technologies Used

- **Languages**: MATLAB, Python
- **Libraries**: TensorFlow, PyTorch
- **Tools**: MATLAB, Jupyter Notebook, GitHub

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bone-fracture-detection.git
