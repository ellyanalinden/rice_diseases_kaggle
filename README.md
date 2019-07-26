# Rice Diseases

## Table of Contents
* Project description
* Development Tools
* Result and Conclusion
* References

## Project description
Building a CNN model using transfer learning (DenseNet 201, VGG16 and ResNet 50) for rice diseases detection

## Development Tools
* PyTorch Framework

## Discussion
The size of the dataset is not too big. Total dataset is 3355. I splitted the dataset into training dataset 80%(2684), validation 10%(335), and testing 10%(336).  
My first attempt was using DenseNet 201 (learning rate of 0.01) and froze all the weights from the pretrained network. The accuracy was very poor, around 50%. Then, I tried another model, VGG16 (learning rate 0.01) and froze all the weights from the pretrained network, accuracy was 39%. ResNet 50 showed the same poor accuracy of 50%.
It showed that the dataset is totally different from original image database.
Then, I set freeze the pretrained weight value.

## Result & Conclusion
Transfer learning with ResNet 50. The accuracy is 80%.

## References
* Kaggle malaria dataset https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria
* Udacity Deep Learning Nanodegree Program
