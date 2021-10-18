---
layout: post
title: "Smooth Camera"
---

![Test gif](/post-doc-muni/assets/zoom-to-cursor.gif)

The first code I actually contributed to this project: camera interaction. Over the years I've developed a camera class that uses smoothing functions for animating the interaction. My first task was to port this into javascript (or rather typescript to be precise).

One of the trickier parts to implement is a 'zoom-to-cursor' functionality, similar to how Google Maps/Earth zooming works. Had to read up on differences between OpenGL and WebGPU coordinate systems. Another thing to learn was working with [gl-matrix](https://github.com/toji/gl-matrix) for vector math.
