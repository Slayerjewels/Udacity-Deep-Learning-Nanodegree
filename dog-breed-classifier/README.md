# Dog Breed Classifier
This repo contains my submission for the CNN Project (Create a Dog Breed Classifier) in Udacity's Deep Learning Nanodegree. Implemented with PyTorch.

## Overview
This algorithm uses transfer learning to predict the dog breed detected in a given image. Given a filepath for an image, the algorithm first determines whether the image contains a dog, a human, or neither. If something other than dog or human is detected, it prints an error message. Given an image of a dog, the algorithm predicts its breed. Given an image of a human, the algorithm predicts the dog breed the image most closely resembles.

## Required Datasets
* [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) containing training, validation, and test images
* [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) for training and testing face detector algorithms
