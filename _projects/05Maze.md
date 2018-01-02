---
title: "Maze"
excerpt: "March 2017: Creates a random maze and then traces a path from the start to the end block."
header:
  teaser: assets/images/Maze.jpg
---

This was a project done in C++ for ICS 46.  The GUI and base was given to us but we created the intelligence that either created a perfect maze (every location is reachable from every other location by exactly one path) or solved any maze if a solution existed.  A perfect maze was created starting with a completely walled-off grid of spaces and using a depth first search.  At every location, the intelligence would check which of the adjacent spaces had been visited and randomly choose the wall between the current space and one of the unvisited adjacent spaces to remove.  To solve the maze, the intelligence could either do a depth first search or breadth first search of the maze, depending on which method the user selects.
