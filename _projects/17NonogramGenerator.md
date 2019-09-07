---
title: "Nonogram Generator"
excerpt: "August 2019: Generates a nonogram puzzle from a provided image"
permalink: projects/NonogramGenerator/
header:
  teaser: assets/images/Nonogram.png
---

This project was done as a fun project after college.  I used Python, Pillow, and colormath  to take a user provided image and convert it to the equivalent nonogram puzzle given a particular color-set.  The first step reduces the size of the image to the size of the final puzzle.  Then, a k-means clustering variation is applied to the pixel colors to reduce the number of colors.  The cluster centers are initialized to the most common color-set colors in the image.  After each iteration, the cluster centers are also reset to the most similar color-set colors.