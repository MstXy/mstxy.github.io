---
layout: page
title: Video Segmentation
description: Video Semantic Segmentation on Cityscapes and CamVid.
img: 
redirect: /assets/pdf/DURF_report.pdf
importance: 2
category: Computer Vision
---

August, 2021

<br>

Through summer 2021, we mainly focused on learning core concepts of several basic models for semi-supervised video semantic segmentation, and trying new twists based on the pre-existing methods. Our Research can be divided into three stages: 
- in the first stage, we spend a month reading past papers and online tutorials to learn the basic structure of image semantic segmentation and video semantic segmentation, like ResNet structures and fully connected networks.
- In the second stage, taking a deeper step in research and implementation of video semantic segmentation, with possible improvements, we referred to the temporal memory attention for video semantic segmentation (TMANet). We intended to increase the accuracy and comparatively improve the computational efficiency of our model based on Camvid and Cityscape—those two datasets. Here are several attempt directions we have accomplished during the DURF program:
- Changing the backbones of the model.
- Adjusting different attention blocks directly at decoding layers.
- Inserting attention block stages among different convolutional layers.
    - non-local attention, pyramid scene parsing strategy, temporal memory attention, crisscross attention, and dual attention
- Reshaping the memory length (the number of consecutive frames we passed into the training model).

Please see <a href="/assets/pdf/DURF_report.pdf" target="_blank">pdf report</a> for more details.

Thank you!

