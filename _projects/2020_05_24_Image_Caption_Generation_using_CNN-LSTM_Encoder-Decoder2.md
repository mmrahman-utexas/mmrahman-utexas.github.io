---
title: "Image Caption Generation using CNN-LSTM Encoder-Decoder2"
collection: projects
urlslug: "Image_Caption_Generation_using_CNN-LSTM_Encoder-Decoder2"
type: "Personal"
permalink: /projects/2020_05_24_Image_Caption_Generation_using_CNN-LSTM_Encoder-Decoder2
contributors: "Md Mesbahur Rahman"
contribution: "Defined and trained a CNN on facial keypoint dataset from YouTube Faces Dataset using custom transformation in PyTorch to perform regression task to predict the location of 68 facial keypoints as inspired from [this paper](https://arxiv.org/pdf/1710.00977.pdf). During inference detected all the faces in an image using OpenCV's pre-trained Haar Cascade classifiers and predicted the location of 68 facial keypoints on those detected faces using our trained CNN network."
date: 2020-05-24
teaserurl: 'image_captioning_infer2.png'
codeurl: 'https://github.com/mmrahman-utexas/Image_Caption_Generator'
excerpt: 'Facial keypoint detection is an important example of a computer vision problem which can be solved effectively by treating the problem as an image regression task and and trainign a CNN network for predicting the image location of the key-points. In this project, I trained a CNN network to predict important facial keypoints given an image of a human face.  I did this project as a requirements of graduating from Udacity's Computer Vision Nanodegree program.'
---

Md Mesbahur Rahman

**Description:**
Image caption generation is a widely used application of sequential generative model. In this project, I designed and trained a CNN-LSTM encoder-decoder architecture for generating caption from an input image. I did this project as part of the requirement of gaduating "Computer Vision Nanodegree" from Udacity.

**My contribution:**
Pre-processed the images in the MS COCO Dataset using PyTorch Transforms and converted the captions in the training set into sequence of integers using BOW vocabulary dictionary with a vocabulary threshold of 5. Defined and trained a CNN encoder and a LSTM Decoder on top of a time distributed embedding layer by using pretrained RESNET50 model as a feature extractor to encode an input image into a fixed
embed sized vector and then used LSTM decoder to generate captions from the output embedding vector of the CNN encoder. Configurations of the data pre-processing and CNN encoder and LSTM decoder were inspired from [this paper](https://arxiv.org/pdf/1411.4555.pdf). Then inference was done on the 'test' portion of the MS COCO dataset.

**Resources:** [[Code](https://github.com/mmrahman-utexas/Image_Caption_Generator)]