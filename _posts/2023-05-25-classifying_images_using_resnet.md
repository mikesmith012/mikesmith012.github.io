# Classifying Real vs Fake Images using ResNet-18 CNN

Table of contents:

1. TOC
{:toc}

## Introduction

Artificial Intelligence has made significant advancements in generating realistic images that can often be indistinguishable from real ones. As a result, the ability to differentiate between real and AI-generated images has become an intriguing and challenging task. In this blog post, we will explore how the ResNet-18 Convolutional Neural Network can be leveraged to classify images as either real or AI generated. [^1]

## Understanding ResNet-18

ResNet-18 is a popular deep learning architecture that has demonstrated excellent performance in various computer vision tasks, including image classification. As the name suggests, it consists of 18 layers. With its deep architecture, ResNet-18 has proven to be a powerful and robust CNN for image classification tasks.

## Results

![](/images/q3_confusion_matrix.png "confusion matrix")

The image classifier did get a few of images wrong as shown in these top losses. But overall was over 95% accurate with the testing set of images! [^2]

![](/images/q3_top_losses.png "top losses")

## Challenges and Considerations

Classifying real vs. AI generated images presents some unique challenges. Since AI-generated images are designed to be realistic, they can closely resemble real images. This requires the ResNet-18 model to be highly sensitive to subtle differences and fine-grained features.

## Footnotes

[^1]: Based off Assignment 3 Question 3 from ELEC4630 - Image Processing and Computer Vision

[^2]: Link to the CIFAKE dataset: https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images
