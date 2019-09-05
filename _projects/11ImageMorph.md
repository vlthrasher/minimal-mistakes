---
title: "Image Morph"
excerpt: "May 2018: Used two images and matching points to blend the two images together"
permalink: projects/ImageMorph/
header:
  teaser: assets/images/ImageMorph.jpeg
---

This project was done as a final project for the computer vision class I took.  It takes two images and, given corresponding points between them, morphs one image into the other.  It first uses Delauney triangulation to triangulate the given points in addition to the corners of the images.  It then uses a non-parametric warp with affine interpolation to slowly shift one image to another.  Because of the triangles, this can be done in a piecewise linear warp so each triangle warp to each corresponding triangle independently.