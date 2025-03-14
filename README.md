# Image Classification Collection Repository

Welcome to the Image Classification Collection Repository! This repository is dedicated to gathering and showcasing implementations of popular deep convolutional neural network (CNN) architectures for image classification tasks. Whether you're a researcher, practitioner, or a deep learning enthusiast, this resource aims to provide a comprehensive collection of state-of-the-art CNN models.

---

## Current Implementation

- **ResNet-34**  
  The current notebook demonstrates how to perform image classification using the ResNet-34 model. It includes detailed sections for:
  - Data loading and preprocessing
  - Model setup using PyTorch’s pre-trained ResNet-34
  - Training and evaluation of the model
  - Visualization of training curves and prediction results

You can explore the ResNet-34 implementation in the [res34_imageClassification.ipynb](./res34_imageClassification.ipynb) notebook.

---

## Planned Updates

We are actively working to expand this repository with additional popular CNN-based methods. Upcoming updates will include implementations for:
- **VGG Networks** (e.g., VGG16, VGG19)
- **Inception Models** (e.g., GoogLeNet, Inception-v3)
- **DenseNet**
- **MobileNet**
- **EfficientNet**
- **Other state-of-the-art architectures**

Stay tuned for updates as we continue to add more models to this collection!

---

## Repository Structure

- **/notebooks**: Contains Jupyter notebooks for different CNN models.
- **/data**: Example datasets or links to external data sources.
- **/models**: Scripts and modules defining the model architectures and training routines.
- **README.md**: This file, which outlines the project details, current status, and future updates.

---

## Requirements

- **Python 3.8+**
- **Jupyter Notebook** or **JupyterLab**

### Python Libraries

- **PyTorch**: Deep learning framework for model implementation.
- **torchvision**: Provides pre-trained models and image transformation utilities.
- **NumPy**: For numerical computations.
- **Matplotlib**: For visualizing data and training metrics.
- *(Optional)* **Pandas**: For data manipulation.

Install the required libraries using:
```bash
pip install torch torchvision numpy matplotlib jupyter
