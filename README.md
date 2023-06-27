# End-to-end Multi-class Dog Breed Identification

## Demo

https://user-images.githubusercontent.com/95677574/235285059-d890b792-5ff4-4c91-9a69-5289eabbc680.mp4


## Overview

This project is an end-to-end multi-class image classifier built using TensorFlow 2.0 and TensorFlow Hub. The main objective of the project is to identify the breed of a dog given an image of a dog. The project is inspired by the scenario where someone takes a photo of a dog at a cafe and wants to know what breed of dog it is.

## Problem

Identifying the breed of a dog given an image of a dog is a challenging task because there are 120 different breeds of dogs. The problem can be solved using deep learning and transfer learning techniques, which are well-suited for working with unstructured data like images.

## Data

The data used in this project is sourced from Kaggle's Dog Breed Identification competition. The dataset consists of 10,000+ labeled images in the training set and 10,000+ unlabeled images in the test set. The data is available on Kaggle's website at https://www.kaggle.com/competitions/dog-breed-identification/.

## Model

The project deals with images, which are unstructured data. Hence, deep learning and transfer learning techniques are used to build an end-to-end multi-class image classifier. The project aims to identify the breed of a dog from 120 different breeds using the labeled data in the training set. The model is then used to predict the breed of dogs in the unlabeled test set.

## Evaluation

The model is evaluated based on the accuracy of the predictions. The evaluation is performed using the Val set, I got 99% accuracy on training set & 80% accuracy on val set. 

## Flask Web Application
In addition to the image classifier, this project includes a Flask web application that allows users to upload images of dogs and get predictions for the breed of the dog in the image. The web application is deployed on an AWS EC2 instance.

## Requirements
To run the notebook and the Flask web application, you will need the following libraries:

tensorflow
tensorflow_hub
flask
Pillow
numpy

## Conclusion
This project demonstrates how to build an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub. The project shows how to use deep learning and transfer learning techniques to identify the breed of a dog from 120 different breeds. The project also highlights the importance of using labeled data in the training set to build an accurate model for predicting the breed of dogs in the unlabeled test set.
