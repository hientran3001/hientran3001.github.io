---
title: "Crowd Counting"
dates: 03-08/2020
image : images/projects/crowd-counting.jpg
author: Tran Quang Hien, Nguyen Phan Khiet Thanh
description : "Graduation thesis. Research problem, build database, baseline, annotation tool."
tags: Python, Laravel Homestead, HTML, CSS 
---

## Description
This is the graduation thesis. We spent 4 months researching this problem and a semester before preparing research skills.
* Input: A video with dense crowd.
* Output: Number of people in video.

First of all, we survey the crowd counting problem with both video and photo inputs, crowd counting applications, the limitations of current methods.

We define a sub-problem: "video crowd counting for density crowd" and find the way to solve it.

All of datasets do not meet our problem, so we build a new dataset.

For annotation, we also build a web application using Laravel Homestead. This website is launched in the MMLab local area network. Only people who have an account and are present in MMLab can annotate.

The website has 2 display:
* User: after logging with their account, user can annotate their assigned videos.

![User](/images/projects/crowd-counting/annotate.jpg)

* Admin: manage users and videos, download annotated files.

![Admin1](/images/projects/crowd-counting/manage.jpg)

![Admin2](/images/projects/crowd-counting/user.jpg)

![Admin3](/images/projects/crowd-counting/video.jpg)

After bulding a dataset, we build baseline to solve the problem. We provide 2 baselines based on FairMOT and JDE.

In the end, we evaluate the baseline and record the results (show in slides).

## Tech stack
#### Python
Main language to train model and evaluate baseline.
#### Laravel Homestead
Use to build a annotation web app.

## Lesson
* Learnt research skills: survey a problem, datasets, current methods; reading documents; find the way to solve the problem;
* Learnt to build a web app with Laravel Homestead.

## Source Code of Annotate Tool
[Github](https://github.com/rysnee/AnnotationTool)

## Slides
[Slides](https://drive.google.com/file/d/1x7PKSj9iYVr7arE3q_OGzq7votwRcjAO/view?usp=sharing)




