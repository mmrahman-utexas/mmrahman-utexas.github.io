---
title: "Unsupervised Anomaly Detection Using Convolutional Autoencoder"
collection: projects
urlslug: "Unsupervised-Anomaly-Detection-Using-Convolutional-Autoencoder"
type: "Academic"
permalink: /projects/2020-05-31-Unsupervised-Anomaly-Detection-Using-Convolutional-Autoencoder
contributors: "Md Mesbahur Rahman"
contribution: "Built an unsupervised dataset from a supervised labeled dataset of MNIST dataset byremoving its labels. Then defined a Convolutional Autoencoder network in PyTorch and trained it on the unsupervised dataset and allowed the network to learn to reconstruct the training images containing regular images with a small percentage of anomaly images. Then during inference, calculated a reconstruction error (MSE) threshold based on a given percent quantile and declared an input image as an anomaly for who's the output image reconstruction error is above the preset threshold."
date: 2020-05-31
teaserurl: 'anomaly-digit.png'
codeurl: 'https://github.com/mmrahman-utexas/Unsupervised_Anomaly_Detection_Using_Convolutional_Autoencoder_Pytorch'
excerpt: 'Anomaly detection is a very common and important problem to solve in industrial setting. There are several aproach exists for doing Anomaly Detection using Deep Learning. One of the most effective (both in terms of performace and model training cost) is to utilie unsupervized anomaly detection using Convolutional Autoencoder. In this project, I designed and trained an Convolutional Autoencoder model for detecting anomaly image (images of digit 3 in MNIST dataset) by considfering images of digit 1 as regular image.'
---

Md Mesbahur Rahman

**Description:**
Anomaly detection is a very common and important problem to solve in industrial setting. There are several aproach exists for doing Anomaly Detection using Deep Learning. One of the most effective (both in terms of performace and model training cost) is to utilie unsupervized anomaly detection using Convolutional Autoencoder. In this project, I designed and trained an Convolutional Autoencoder model for detecting anomaly image (images of digit 3 in MNIST dataset) by considfering images of digit 1 as regular image.

**My contribution:**
Built an unsupervised dataset from a supervised labeled dataset of MNIST dataset byremoving its labels. Then defined a Convolutional Autoencoder network in PyTorch and trained it on the unsupervised dataset and allowed the network to learn to reconstruct the training images containing regular images with a small percentage of anomaly images. Then during inference, calculated a reconstruction error (MSE) threshold based on a given percent quantile and declared an input image as an anomaly for who&apos;s the output image reconstruction error is above the preset threshold.

**Resources:** [[Code](https://github.com/mmrahman-utexas/Unsupervised_Anomaly_Detection_Using_Convolutional_Autoencoder_Pytorch)]
