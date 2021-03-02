---
title: "Image Retrieval System"
dates: 04/2020
image: images/projects/ir2.jpg
author: Tran Quang Hien, Phan Quoc Tuan
description : "A website that retrieve top images in database related to input image."
tags: Python, Django, HTML, CSS   
---

## Description
 This is the project for "Multimedia Information Retrival" course. We will rank top N relevant images from database to the query image. The Oxford Buildings Dataset consists of 5000+ images.
* Input: An image.
* Output: Top N relevant images.

## Tech stack
#### Python
With the user image input, we compute the VLAD feature using the feature extractor and then compare it with the feature-extracted database. We use ball-tree to index features for faster retrieval. Output of this step is an index of top N related images.
#### Django
Use to build a web app with 2 module:
* User input an image and crop if they want.
* Retrieve and show output.

## Lesson
* Learnt retrieval technology.
* Learnt to build a web app with Django.

## Source Code
[Github](https://github.com/rysnee/DoAn/)

## Demo
{{< youtube bXESjQjqWyU >}}


