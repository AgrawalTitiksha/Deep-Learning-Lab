## Color Detectio using Deep Learning

#### Dataset: 
https://www.kaggle.com/datasets/adikurniawan/color-dataset-for-color-recognition

#### Models:
###### 1) DenseNet Model:
A DenseNet is a type of convolutional neural network that utilises dense connections between layers, through Dense Blocks, where we connect all layers (with matching feature-map sizes) directly with each other. To preserve the feed-forward nature, each layer obtains additional inputs from all preceding layers and passes on its own feature-maps to all subsequent layers.
###### 2) Inception Model:
Inception v3 is an image recognition model that has been shown to attain greater than 78.1% accuracy on the ImageNet dataset. 
###### 3) MobileNet Model:
MobileNet is a class of convolutional neural network (CNN) that was open-sourced by Google, and therefore, provides an excellent starting point for training classifiers that are insanely small and insanely fast. They can be built upon for classification, detection, embeddings and segmentation.

#### Accuracies:
DenseNet: 89.30%
Inception: 85.40%
MobileNet: 96.60%
