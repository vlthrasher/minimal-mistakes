---
title: "Directions"
excerpt: "May 2017: Finds the shortest route by distance and by time between two locations"
permalink: projects/Directions/
header:
  teaser: assets/images/Road.jpg
---
This was a project done in C++ for ICS 46.  The input consisted of a text file with a list of locations followed by the streets connecting them and how much distance and time each required.  Finally the text file listed the routes it wanted you to find either by best distance or time.  My program parsed this input and generated a graph represented by an edge list.  For each of the routes, Dijkstra’s algorithm was run either focusing on time or distance depending on what was specified.
