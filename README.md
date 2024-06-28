# ASSIGNMENT_09
Image Classification Model Development



# Image Classification Project

This project involves building a machine-learning model to classify images into six categories: buildings, forest, glacier, mountain, sea, and street.

## Setup

### Prerequisites

- Python 3.6+
- TensorFlow 2.x
- Keras
- OpenCV
- Numpy
- Pandas
- Matplotlib

### Installation

Install the required packages using pip:

```bash
pip install tensorflow keras opencv-python numpy pandas matplotlib




### Dataset
Ensure you have the dataset structured with images in directories named after their respective labels.

### Model
Architecture: Convolutional Neural Network (CNN)
Layers:
Conv2D, MaxPooling2D, Flatten, Dense
Activation Functions: ReLU, Softmax
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy

### Evaluation
The model is evaluated on a test set, and the test accuracy is printed. Further metrics can be added as needed.

### Results
Test Accuracy: 0.79666668176651
