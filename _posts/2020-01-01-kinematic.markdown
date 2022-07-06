---
layout: post
title:  "Spiral scanning approach for near-zero-drift mapping in Webots Simulator"
time: "January - June 2022"
image: /images/webots.gif
categories: research

authors: "<strong>Xinzhi Yan</strong>, Gunjas Singh"
---
To improve our slam backend, a brand new idea has been implemented for solving long distance drift. The difference between the current sensor payload and the new idea is the scanning pattern. Over longer scans, this drift accumulates as the system relies entirely on the visual-inertial odometry that gives an accurate estimation of the robot pose. In our new method, instead of using a laser ring projector, we plan to use a normal laser line projector and a camera, and they revolve around the pipe’s axial axis. The advantage of this method is that while revolving, after one revolution, it will scan the same physical location twice, the first being in the previous revolution. Using this, we can perform a loop closure and correct the drift after each revolution in real time. 

