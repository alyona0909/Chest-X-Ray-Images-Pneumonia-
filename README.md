# Chest-X-Ray-Images-Pneumonia

In this notebook, we're going to detect and classify human diseases from medical images.

## Data 

The data we're using is from Kaggle : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

The dataset `chest_x_ray.zip` is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Can deep learning determine if a person has a pneumonia?

## Content

* `Pneumonia.ipynb`

This file turns all images to Tensors and builds a neural network that classifies images.
