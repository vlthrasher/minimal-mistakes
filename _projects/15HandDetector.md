---
title: "Hand Detector"
excerpt: "March 2019: Uses a NN and CV to classify hands in images"
permalink: projects/HandDetector/
header:
  teaser: assets/images/Hand.jpeg
---

This project was done as a final project for the AI Project class at UCI.  We used Pytorch to develop a hand classifier using multiple methods.  One of the methods was just a standard deep neural network, another was a deep neural network on images that had been preprocessed for skin-detection, and a third implemented feature detection.  We decided to use ImageNet images because they would produce enough variety in subjects to reduce the risk of overtraining.  My job was to create the data banks we were to use as well as to develop the neural network to be used with skin-detected images.