# AlexNet Implementation 
> **A Transfer Learning Approach using Pytorch**

The Evolving amount of Data and processing level of GPU's helped the researchers in the field of Deep Learning to perform better computations using the largely available data in order to produce better results regarding the tasks of Deep Learning like Compter Vision and Natural Language Processing.

One such evolution in the field of Computer is Vision is AlexNet - [ImageNet Classification with Deep Convolutional
Neural Networks](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)

This architecture was designed in the year 2012 by Alex Krizhevsky in collaboration with his Ph.D Advisor - Geoffrey Hinton and Ilya Sutskever with 89098 citations as of today.

It competed in ILSVRC ' 2010 and ILSVRC ' 2012. 

This paper is considered as one of the most influential paper in the field of Computer Vision. The architecture of the model is comparitively similar to that of LeNet with some additional depth of layers and regularization method called "[Dropout]"(https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf) which helps in reducing the effect of overfitting. This paper provides an intuition about working on Deep Convolutional Layers along with usage of Non-Saturating non-linearity called as ReLU and regularizations like [Data Augumentation](https://en.wikipedia.org/wiki/Data_augmentation) and Dropout.

## Task
To predict the class label of an image given as input from the provided dataset (CIFAR-10).

## Datasets
CIFAR-10 Dataset

_(Provided)_

This Dataset involves **50000 training samples** and **10000 testing samples** classified into **10 different classes**.

Each image is a 3-channeled sample (RGB)

## Requirements
Python >= 3.0

PyTorch Version >= 0.4.0

torchvision >= 0.2.1

## Architecture


## Obtained Accuracy
Accuracy Obtained after Pre-Training = **86.57 %**

Accuracy Obtained after Fine-Tuning = **87.18 %**

## Obtained Outputs
#### **Outputs Obtained After Pre-Training :**

![pt](https://user-images.githubusercontent.com/67636257/124396219-d4e15e00-dd25-11eb-9ada-3f75543d2914.png)

![pt1](https://user-images.githubusercontent.com/67636257/124396221-d579f480-dd25-11eb-9323-20c6029a456a.png)

![pt2](https://user-images.githubusercontent.com/67636257/124396207-d01caa00-dd25-11eb-9f04-b75c4a378a97.png)

![pt3](https://user-images.githubusercontent.com/67636257/124396210-d1e66d80-dd25-11eb-9de7-87d47b32e9d9.png)

#### **Outputs Obtained After Fine-Tuning :**

![ft](https://user-images.githubusercontent.com/67636257/124396211-d27f0400-dd25-11eb-9b54-0b7409357c1b.png)

![ft1](https://user-images.githubusercontent.com/67636257/124396213-d27f0400-dd25-11eb-9356-b234831be933.png)

![ft2](https://user-images.githubusercontent.com/67636257/124396215-d3b03100-dd25-11eb-9694-fe3c3eed9ff9.png)

![ft3](https://user-images.githubusercontent.com/67636257/124396217-d448c780-dd25-11eb-9069-14b1be6d5a23.png)

