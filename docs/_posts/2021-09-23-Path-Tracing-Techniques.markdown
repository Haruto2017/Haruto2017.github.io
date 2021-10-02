---
layout: post
title:  "Path Tracing Techniques"
date:   2021-09-23 13:44:00 -0700
categories: learning note
---
Refering to [Yan's intro class to Real-Time Rendering][Game101-Class] and [Yan's intermediate class on High-Quality Real-Time Rendering][Game202-Class].

RayTracing is used in computer rendering to make multi-bounce lighting aka. global illumination possible in 3d games and movies. 

[Game101-Class]: https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html
[Game202-Class]: https://sites.cs.ucsb.edu/~lingqi/teaching/games202.html
[Game101-Class-13]: https://sites.cs.ucsb.edu/~lingqi/teaching/resources/GAMES101_Lecture_13.pdf
[Game101-Class-14]: https://sites.cs.ucsb.edu/~lingqi/teaching/resources/GAMES101_Lecture_14.pdf
[Game101-Class-15]: https://sites.cs.ucsb.edu/~lingqi/teaching/resources/GAMES101_Lecture_15.pdf
[Game101-Class-16]: https://sites.cs.ucsb.edu/~lingqi/teaching/resources/GAMES101_Lecture_16.pdf