---
layout: post
title: "Deadshot Robot Code"
---

## Introduction

This is the code for my robotics team's 2020/2021 robot, Deadshot. Deadshot was coded primarily in LabVIEW but our team decided to add on ROS to improve automous features. This was my third and fourth year on the programming subteam and took on more responsibilities. I was the director of programming and led the development of multiple subsystems and troubleshooting.

## Subsystems

### Colorwheel

I was in charge of programming the colorwheel, which utilized a color sensor to automatically detect the current color and spin the wheel accordingly. By creating an autonomous control, it enabled the drivers to spend more time focusing on the shooting aspect of the game.

### Shooter

For the shooter subsystem, I was in charge of implementing the shooter algorithmn that determined the hood angle and RPM of the flywheel when given the distance from the target. After attempting various methods including non-linear regressions and holding RPM steady, we settled on using interpolation between known values, giving us one of the most accurate shooters in the world.

### Climb

To aid with the climb, I developed an auto-climber that would automatically raise the hooks to the proper height when preparing for climb.

## Git Project

The repository for the project is not currently public but if the code is released, I will post an update.

## Moving Forward

This is the end of this project as the 2020/2021 FRC season comes to a close. This was my last year of robotics and it has truly been a blast.
