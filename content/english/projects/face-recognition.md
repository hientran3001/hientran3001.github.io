---
title: "Face Recognition"
dates: 06/2019
image : images/projects/face-reg.jpg    
author: Tran Quang Hien, Phan Quoc Tuan, Nguyen Thanh Trung
description : Realtime Face Detection and Recognition with video input.
tags: Python 
---

## Description
The client's face recognition system with a direct viewing angle.
* Input: A video from camera.
* Output: face bounding boxes and recognite for those faces.

![Baseline](/images/projects/face-rec/baseline.jpg)

We first find the faces in the image using MTCNN, then crop them to extract the features. After performing experiments, we found ArcFace to be the best model for this step. We then compared the extracted features in the database for face recognition, and Faiss was our pick.

#### Result
![Result](/images/projects/face-rec/result.jpg)

## Tech stack
#### Python
Main language for computer vision task.

## Lesson
* Learnt face detection models.
* Learnt feature extraction models.
* Learnt retrieval methods.

## Source Code
[Google Drive](https://drive.google.com/file/d/1zk0mEQl5x7RyFAv-rTrpSMr7PQbA_Jn6/view?usp=sharing)




