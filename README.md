# Fire_detection
*Final project of Deep Learning, USF MSDS program*


# Description

This project is to build a classifier to detect if the image contains fire by using Pretrained Resnet34.

The dataset is from https://www.kaggle.com/phylake1337/fire-datase.

There are 755 fire images and 244 non-fire images. Fire images contains fire and smoke while non-fire images contains forest, river, etc.

We divided the dataset into train : validation : test = 60% : 20% : 20%.


# Contributors
[Boliang Liu](https://www.linkedin.com/in/boliang-liu/) <br>
[Huidong Xu](https://www.linkedin.com/in/huidong-xu/)

<img src = './Readme/fire.69.png' height = 250>            <img src = './Readme/non_fire.98.png' height = 250>


# Model

In this project, we used 3 techniques/model:

1. Data Augmentation

For train set: Random crop; Rotate; Flip
For test set: Center crop

2. Model

Pretrained Resnet34: Remove the last two layers; Divide layers into two parts; Add a sequential layer

3. Different Learning Rates

1st group: 0.001/9
2nd group: 0.001/3
3rd group: 0.001



# Outcomes

