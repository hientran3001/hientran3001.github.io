---
title: "Augmented Reality"
dates: 06/2019
image : images/projects/ar1.jpg
author: Tran Quang Hien, Nguyen Cao Nguyen Lam, Phan Quoc Tuan
description : An application that get input from webcam, detect patterns and show 3D model on them.
tags: Python 
---

## Description
A project named "AR for Kid". Although there are many libraries for this problem, we do it from scratch to learn how it works.
* Input: A video from webcam.
* Output: Show related 3D model on detected pattern.

When get an image from webcam, we use SIFT to detect patterns, then we find the homography matrix to transform pattern coordinates to image coordinates. After that, we keep finding the 2D to 3D matrix. In the end, the 3D model is loaded and shown on input image.

## Tech stack
#### Python
Main language for computer vision task.

#### OpenGL
API for working with 3D model.

## Lesson
* Learnt detecting patterns.
* Learnt 2D to 2D axis transformation.
* Learnt 2D to 3D axis transformation.

## Source Code
[Google Drive](https://drive.google.com/file/d/14G-HGohme2RjjLgfnSTzFTlPZ8B_xZSS/view?usp=sharing)




