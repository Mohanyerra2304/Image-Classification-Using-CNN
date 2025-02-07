
## Overview
This project demonstrates how to use Convolutional Neural Networks (CNN) for image classification. We use the CIFAR-10 dataset, which contains 60,000 32x32 color images across 10 distinct classes, including airplanes, cars, birds, and more. The aim is to accurately classify these images into their respective categories.

## Dataset
The **CIFAR-10** dataset consists of 60,000 color images in 10 classes, with 6,000 images per class. It’s split into:
- **Training Images**: 50,000
- **Test Images**: 10,000

### Classes
The dataset’s classes are as follows:
- **Airplane**
- **Automobile**
- **Bird**
- **Cat**
- **Deer**
- **Dog**
- **Frog**
- **Horse**
- **Ship**
- **Truck**

## Model Architecture
Our CNN model follows a straightforward architecture designed to handle image classification:

1. **Convolutional Layers**: Capture spatial features from images.
2. **Pooling Layers**: Down-sample feature maps, reducing computation and controlling overfitting.
3. **Dense Layers**: Fully connected layers for classification.

The final layer is a softmax layer, which outputs probabilities across the 10 classes.

## Training and Evaluation
The model is trained using the **Adam optimizer** and a **sparse categorical cross-entropy** loss function. After training, the model is evaluated on the test set, achieving an accuracy of around **70-75%**.





