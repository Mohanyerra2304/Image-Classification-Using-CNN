#Image Classification using Convolutional Neural Networks (CNN) on CIFAR-10 Dataset
##Overview
This project demonstrates how to use Convolutional Neural Networks (CNN) for image classification. The CNN model is trained on the CIFAR-10 dataset, which contains 60,000 32x32 color images in 10 distinct classes, including objects like airplanes, cars, birds, cats, and more. The goal is to classify images accurately into these categories.
##Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.   
The classes are:  
Airplane  
Automobile  
Bird  
Cat  
Deer 
Dog  
Frog  
Horse  
Ship  
Truck  
The dataset is divided into 50,000 training images and 10,000 test images.  

##Model Architecture
The CNN model is a simple yet effective architecture for image classification tasks. It consists of:  
**Convolutional Layers:** Capture spatial features from images.  
**Pooling Layers:** Down-sample the feature maps, reducing computation and control overfitting.  
**Dense Layers:** Fully connected layers for classification.  
The model uses a softmax layer to output probabilities across the 10 classes.  

##Training and Evaluation
The model is trained for 10 epochs using the Adam optimizer and a sparse categorical cross-entropy loss function. After training, the model is evaluated on the test set, achieving approximately 70-75% accuracy.

##Training Parameters:
Epochs: 10   
Batch Size: 32  
Optimizer: Adam  
Loss Function: Sparse Categorical Cross-Entropy  
