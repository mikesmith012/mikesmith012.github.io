# Introduction to Deep Learning

Table of contents:

1. TOC
{:toc}

## Introduction

In the first module of the fastai course, we explored the fundamentals of deep learning. We started by understanding the basic building blocks of neural networks, including neurons, activation functions, and layers. I was amazed to see how these simple components can be combined to create powerful models capable of complex tasks.

## First Image Classifier

Firstly, we dived into the world of image classification. By leveraging pre-trained models such as ResNet, we were able to achieve impressive accuracy on image recognition tasks with just a few lines of code! My first program involved classifying ten different classes of animals based on sample images that were scraped off the web [^1]. Here are the ten animals that I classified:

1. Whale
2. Tiger
3. Cheetah
4. Zebra
5. Dog
6. Cat
7. Goat
8. Penguin
9. Lizard
10. Ant

## Results

The results of the classifer were really impressive. Here is the resulting confusion matrix and t-SNE projections:

![](/images/confusion_matrix.png "confusion matrix")

![](/images/tsne_projection.png "tsne projection")

The image classifer did get a couple of images wrong as shown in these top losses. But overall really good as a first image classifer!

![](/images/top_losses.png "top losses")

## Highlights

One of the highlights was learning about the fastai library. Its high-level abstractions and intuitive APIs make it incredibly user-friendly, enabling rapid prototyping and experimentation. I appreciated the emphasis on practical implementation and the balance between theory and hands-on coding.

## Footnotes

[^1]: Based off Assignment 3 Question 2 from ELEC4630 - Image Processing and Computer Vision

