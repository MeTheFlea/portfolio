---
index: 2
layout : project

imgDir: /images/Pathtracer/
imgCount: 5
bin: /binaries/Pathtracer-bin.zip
source: Source files available upon request.
title : Multithreaded CPU Pathtracer
tech: 
- C++
- Multithreaded with a Job System

sections : 
 Description :
 - "A pathtracer written in C++ that continuously updates and converges on the final image as long as the camera remains stationary. With support for HDR skydomes and depth-of-field, this makes scenes rendered in the pathtracer look incredibly realistic."
 - "As a pathtracer is inherently quite slow (especially one on the CPU), a number of steps were taken in order to optimise the application. Please refer to <b><a target=\"report\" href=\"/files/MartinStuurwold_PathtracerReport.pdf\">this report</a></b> to read in-depth explanations to my optimisations as well as specific features implemented."

features : 
- "Continuosly converges on the final image."
- "Bounding Volume Hierarchy (BVH) for optimisation."
- "Multithreaded job-system."
- "Ambient occlusion."
- "Caustics through glass."
- "Colour bleeding."
- "Depth of field."
---

