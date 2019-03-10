---
layout:     post
title:      Gyro stabilisation of RC plane
date:       2019-03-10
author:     RohitTembhare
summary:    Short writeup about my project.
categories: projects
thumbnail:  jekyll
tags:
 - Aeromodelling
 - Arduino
 
---

I did this project as a part of Institute Technical Summer Project. It primarily involved making the radio controlled(RC) plane stable and semi-autonomous. We used Arduino microcontroller for gathering the orientation data using inertial measurement unit IMU 6050 and then processing it to give correct output to servo motors which controlled control surfaces of the plane. Output was given using PID controller library.

 You can find Arduino code [here](https://github.com/aerorohit/ITSP_gyro_stabilisation)