---
title: MIT BeaverWorks Summer Insitute Final Project
draft: False
date: 2021-08-30
description: "Autonomous quadcopter navigation through hoops"
---

![Missing Propellers](images/missing_props_prize.jpg)
As our [MIT BeaverWorks Summer Insitute](https://beaverworks.ll.mit.edu/CMS/bw/bwsi) final project in 2021, Nandini Bezwada, Michelle Wang, and I programmed drones to fly through colored hoops autonomously. Our project won the best final project award.

We used OpenCV's solvePnP function to project 2D pixels into 3 dimensions. The drone positions itself using four PID controllers for x, y, z, and yaw. 
![3rd Persion View](https://media.giphy.com/media/yDqiu2abl0OyRYQyoA/giphy.gif)

The drone records footage of its flights so that we can replay what it saw before crashes.
![Corner](https://media.giphy.com/media/lyELslfCHNIZID92PT/giphy.gif)
The drone also records footage with a debugger overlay which displays the color filter, ellipse fitting, solvePnP axes, and variables. The debugger helped us determine the root cause of every crash.
![Debugger](https://media.giphy.com/media/58h8fLbwHo1lWn5DEg/giphy.gif)
![Overlay](https://media.giphy.com/media/yilzbCmvF5zGn7Rp9Z/giphy-downsized-large.gif)

For more details, see our presentation video:
{{<youtube lFV6kygEo7g>}}