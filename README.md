# Tea-Leaf-Disease-Classification-using-CNN
This project trains a convolutional neural network (CNN) to classify tea leaf diseases from images. The model can identify 8 different types of leaf conditions including healthy and diseased leaves.

## Dataset

Dataset used is organized in class-wise folders:
- Anthracnose
- Algal leaf
- Bird eye spot
- Brown blight
- Gray light
- Healthy
- Red leaf spot
- White spot

> Path: `/content/drive/MyDrive/tea sickness dataset/`

## Model Architecture

- 4 convolutional layers with `ReLU` and `MaxPooling`
- Dropout + L2 Regularization
- Final softmax output over 8 classes

## Accuracy

Achieved validation accuracy of **73%+** after 30+ epochs.


## Dependencies

Python 3.8+

TensorFlow

NumPy

scikit-learn

matplotlib
