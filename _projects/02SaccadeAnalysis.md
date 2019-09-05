---
title: "Saccade Analyzer"
excerpt: "July 2013: Takes eye tracking data collected and looks to see if a saccade occured."
permalink: projects/SaccadeAnalyzer/
header:
  teaser: assets/images/1.png
---

This project was completed as part of my [high school research internship at RIT](/work/RIT_Intern/).
In this I parsed through a data set that was collected when a previous eye coordination experiment was done.
I graphed the data points of the velocity of eye movements and placed a Gaussian filter over the top to smooth out the curve.
I then analyzed this curve to determine if there was a saccade of interest by looking at features like the maximum velocity, the acceleration, and the time of the peak velocity.
The code for this can be found in [RIT-Gaze-Study repository](https://github.com/vlthrasher/RIT-Gaze-Study).
