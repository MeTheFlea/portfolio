---
index: 4
layout : project

imgDir: /images/GPGPU/
imgCount: 3
bin: /binaries/GPGPU-bin.zip
source: Source files available upon request.
title : Cloth Simulation on the GPU
tech: 
- C++
- OpenGL Compute shaders

sections : 
 Description :
 - "A learning experience in trying to use the GPU for general purpose calculations. I had previously worked extensively with visual shaders (vertex/geometry/fragment) but this was the first time I explored compute shaders. The scene consists of a piece of cloth hanging above a terrain. You can move the cloth around and it will collide with the terrain."
 - "The cloth is a subdivided mesh, and each vertex's position is integrated over time using Verlet integration. This Verlet integration is done multiple times each frame (for stability) on the GPU so that to maintain a realtime framerate."

features : 
- "OpenGL Compute shaders to offload calculations to the GPU."
- "Procedurally generated textures and terrain."
- "Cloth collides with terrain geometry."
---

