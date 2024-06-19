---
layout: page
title: Formula Racing
permalink: /engineering/formula
---

![susteam](/assets/img/formula/NFR22team.jpg)  

I was a member of the suspension subteam on Northwestern Formula Racing from 2021-2023. I designed and manufactured the steering system and uprights. I had many amazing mentors and teammates, and I greatly enjoyed teaching younger members essential skills like CAD and metal machining.

# Steering

## Design

![Ackermann Gif](/assets/img/formula/ackermannsteer.gif)  

This animation shows steering powered by a rack and pinion. In my design, I started with the minimum turn radius on the track to define the steering geometry following the Ackermann model.

![Ackermann Gif](/assets/img/formula/ackermansketch.png)  


I then created a SolidWorks assembly of the system. I used torsional stress equations and FEA to ensure parts could withstand the loads within a factor of safety.  

![CAD Assembly](/assets/img/formula/steering_frame_assembly.jpg)  

## Manufacturing

We manufactured parts using manual mills, lathes, and CNC machines. We had tight tolerances to minimize play in the system.  

![steering in frame](/assets/img/formula/steering_in_frame.jpg)

# Uprights

<p float="left">
  <img src="/assets/img/upright.png" width="300" />
  <img src="/assets/img/formula/notire.png" width="300" /> 
</p>

## Design

<p float="left">
  <img src="/assets/img/formula/uprightsketch1.jpg" width="300" />
  <img src="/assets/img/formula/uprightsketch2.jpg" width="300" /> 
</p>  

The uprights undergo very high stresses during braking and cornering. They connect the frame to the wheels, so preventing failure is paramount. At the same time, these parts need to be as light as possible to maximize speed.

![FEA](/assets/img/formula/fea.png)

## Manufacturing

I made manufacturing drawings with GD&T for critical surfaces like bearing bores. The uprights house a lot of critical parts like wheel hubs, brake calipers and speed sensors. This part was made on a 3-axis CNC.  

<iframe src="/assets/img/formula/uprightdrawing.pdf" style="width:100%; height:500px;" frameborder="0"></iframe>





