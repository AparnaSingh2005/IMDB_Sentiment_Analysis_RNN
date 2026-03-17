# CNN for CIFAR-10 Image Classification

A Convolutional Neural Network (CNN) built using TensorFlow/Keras to classify images from the CIFAR-10 dataset.
This project demonstrates deep learning fundamentals including convolution layers, pooling, activation functions, regularization, model training, and performance evaluation.

## Dataset

The model is trained on the **CIFAR-10** dataset:
- 60,000 32x32 RGB images
- 10 object classes
- 50,000 training images
- 10,000 testing images

Classes:
Airplane | Automobile | Bird | Cat | Deer | Dog | Frog | Horse | Ship | Truck

## Model Architecture

The CNN architecture includes:

- Conv2D Layers
- ReLU Activation
- MaxPooling Layers
- Dropout (Regularization)
- Fully Connected Dense Layers
- Softmax Output Layer

Architecture Flow:

Input → Conv2D → ReLU → MaxPool → Conv2D → ReLU → MaxPool → Flatten → Dense → Dropout → Softmax


## Model Performance 
**Test Accuracy:** **74.71%**  

Achieving 74.71% accuracy demonstrates strong baseline CNN implementation on CIFAR-10 without transfer learning.

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook




