# Brain Tumor Segmentation using Kernel Ensemble Learning

## Table of Contents
- [Project Overview]
- [Features]
- [Tech Stack]
- [Installation]
- [Contact]

## Project Overview
Brain Tumor Segmentation using Kernel Ensemble Learning is a deep learning-based project aimed at accurately segmenting brain tumors from MRI scans. By leveraging advanced techniques such as Feature Enhancer (FE) blocks, custom loss functions, Kernel Ensemble Learning (KEL), and ensemble learning, the project improves segmentation accuracy, particularly for small-scale tumor detection and spatial preservation.

## Features
- **Feature Enhancer (FE) Block:** Extracts middle-level features from shallow layers to improve tumor identification.
- **Custom Loss Functions:** Addresses class imbalance, enhancing segmentation performance over existing methods.
- **Kernel Ensemble Learning (KEL):** Captures both local and global features to enhance segmentation accuracy.
- **Ensemble Learning:** Combines multiple models to improve small-scale tumor detection and maintain spatial preservation.

## Tech Stack
- **Programming Language:** Python 3.10
- **Development Environment:** Jupyter Notebook
- **Deep Learning Frameworks:** PyTorch or TensorFlow
- **Machine Learning Libraries:** scikit-learn
- **Scientific Computing Libraries:** NumPy
- **Data Visualization Libraries:** Plotly, Matplotlib, or Seaborn
- **Image Processing Libraries:** OpenCV (cv2) or Pillow

## Installation

### 1. Clone the Repository

`git clone https://github.com/ak736/Brain-Tumor-Segmentation.git`
<br />
`cd brain-tumor-segmentation`

### 2. Set Up the Environment
**Using virtualenv**

`python3.10 -m venv venv`
<br />
`source venv/bin/activate`

**Or using conda**

`conda create -n brain_tumor_segmentation python=3.10`
<br />
`conda activate brain_tumor_segmentation`

### 3. Install Dependencies
**Using pip**

`pip install -r requirements.txt`

## Contact
For any inquiries or support, please contact aniketkir63@gmail.com


