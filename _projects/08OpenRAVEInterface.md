---
title: "OpenRAVE Interface"
excerpt: "July 2017: Generates a GUI that runs alongside an OpenRAVE rendering to allow easier adjustments."
permalink: projects/OpenRAVE/
header:
  image: 
  teaser: assets/images/OpenRAVEHand.png
---

This project was done in python during my [Oregon State REU Internship](https://vlthrasher.github.io/work/01OSU/).  OpenRAVE is an open source toolkit used mostly to render representations of robots.  My lab group had already established a 3D representation of the Barrett Hand (the 3-fingered robotic hand we were focusing on) and a base for rendering the hand with another object in the same scene.  However, because everything in this base was represented by numbers on a different system than the typical 360 degrees and (0,0,0) origin, it became very time consuming to find the values we wanted for our specific representations.  I built a GUI that utilized the base that included sliders for the hand position, orientation and finger closure in addition to radio buttons to specify which object and what size object were required.  Finally, contact checking was also established so the fingers and hand could not move through the middle of the object.  A demonstration of this can be seen [here](https://vlthrasher.github.io/assets/images/out-5.mp4)
