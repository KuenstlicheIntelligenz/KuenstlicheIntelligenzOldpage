---
layout: post
title:  "Ways to improve an image model"
categories: [deeplearning]
tags: [image, preprocessing]
---

- Normalize images to [-1,1] (or [0,1])
- Whiten images
- Try to resize them as little as possible. Consider making models for different image sizes.
- Ive experienced bilinear resizing to be the best. Consider other methods.
- Use ExponentialMovingAverage for evaluation
