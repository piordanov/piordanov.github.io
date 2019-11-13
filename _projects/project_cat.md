---
layout: project
author: Peter Iordanov
title: Project Cat
year: Spring 2017
category: projects
order: 3
---

For our group project in CS 498 VR (then taught by Steven M. Lavalle), I worked in a team of four to create a multiplayer virtual reality fighting game. Our goal was to create an experience close to fighting, but we would not be able to have players physically rough-house each other. We decided to recognize a series of gestures using players' arms to spawn and defend from projectiles, while they would use the Oculus controller's joysticks to move and avoid attacks.

The gestures we tracked for were:
* upward/downward slash for a slash attack
* outward swipe of the forearm to throw a shuriken
* holding hands up to defend with a shield

<img src="https://raw.githubusercontent.com/piordanov/ProjectCat/master/Assets/projectcat_tutorial.png" height="480" />

A lot of my work focused on the networking layer of the game using Photon Cloud, ensuring low latency so users wouldn't experience vr-sickness inducing lag and tracking successful hits from each player.

<!-- A Virtual Reality project for class CS 498 VR where several developers and designers (including myself) made a multiplayer fighting game. We made our own hand tracking controls and set up multiplayer networking using Photon Cloud. -->
<iframe src="https://drive.google.com/file/d/1anI2-cZuAbMHGTOqf4EZFgSPcyY_O0mc/preview" width="640" height="480" frameborder="0" allowfullscreen></iframe>

Our project's source code is available on [Github](https://github.com/piordanov/ProjectCat).