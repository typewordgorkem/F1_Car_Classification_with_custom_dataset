# F1_Car_Classification_with_custom_dataset

This repository contains a Python implementation of F1 car classification using custom datasets. The goal of this project is to train a deep learning model to accurately classify different F1 cars based on images of the cars.

### Overview

In this project, we use several pre-trained deep learning architectures such as GoogLeNet, ResNet50, and VGG11 as the base models. These models have already been trained on a large dataset, so we can use their weights as a starting point for our own classification task. The custom dataset used for fine-tuning the models is comprised of images of F1 cars from various teams and seasons.

### Getting Started

#### Prerequisites

- Python 3.6 or higher
- Tensorflow 2.x
- Numpy
- Matplotlib
- OpenCV
- Pandas
- Seaborn

### Installing
1. Clone the repository
```
git clone https://github.com/typewordgorkem/f1-car-classification.git
```
2. Just compile on Jupyter Notebook or supported IDE's.

### Results
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The best results were obtained using the ResNet50 architecture, achieving an accuracy of 96% on the validation set.

### Conclusion
This project demonstrates the use of fine-tuning pre-trained models for object classification tasks using custom datasets. The models can be further improved by using techniques such as data augmentation and hyperparameter tuning. As a next step, it would be interesting to apply this approach to other object classification tasks and compare the results.



