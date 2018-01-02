---
title: "Wumpus World AI"
excerpt: "October 2017-December 2017: AI player that explores a static unknown world looking for gold and avoiding death"
permalink: /WumpusWorld/
header:
  teaser: assets/images/Wumpus.png
---

This project was completed in python with a partner as part of the Intro to AI class.  
Environment Assumptions
- The agent always started in the bottom left corner of the field of the cave and started facing right
- The cave consisted of a grid of 4-7 rooms by 4-7 rooms
- The agent could only move to adjacent squares
- The wumpus' adjacent squares had a stench percept
- Each room had a 20% chance of being a deadly pit
- All pits' adjacent squares had a breeze percept
- +1000 for collecting the gold
- -1000 for death by either wumpus or pit
- -1 for every action take (moving, changing direction, picking up gold,...)
Our AI's strategies: 
- Use a depth first traversal to move around the cave, backtracking when a percept is observed
- Of the adjacent rooms that have not been visited, choose the one that requires the least amount of turning
- Use a probability matrix to represent which rooms have been visited (probability of gold) as well as which rooms probabily have pits or the wumpus
- If a stench is smelled immediately, shoot the arrow to the right and continue with a depth first traversal
- Once the wumpus' location is known, ignore all stenches and just ignore the wumpus square
