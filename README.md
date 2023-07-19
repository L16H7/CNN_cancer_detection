## Image binary classification
This is a basic Convolution Neural Network classification and transfer learning with EfficientNet using pytorch.

## Data
The data is from Histopathologic Cancer Detection competition. https://www.kaggle.com/competitions/histopathologic-cancer-detection/submissions#

## Experiment 1
## Model Description:
The SimpleCNN model is a basic convolutional neural network designed for image classification tasks. It consists of two main components: convolutional layers and fully connected layers. The model takes input images with three color channels and predicts the class label.

## Experiment 2
## EfficientNet
Used EfficientNet and changed the classifier to binary classification.

### Training Details
Loss Function: Binary Crossentropy<br>
Optimizer: SGD (learning rate: 0.001)<br>
Batch Size: Configurable<br>
Number of Epochs: 5 (configurable)<br>
Validation Data: Utilizes a separate validation dataset<br>

### References
Official Pytorch tutorial<br>
https://pytorch.org/tutorials/beginner/introyt/modelsyt_tutorial.html?highlight=convolution

Kaggle Discussions<br>
https://www.kaggle.com/competitions/histopathologic-cancer-detection/discussion?sort=votes
