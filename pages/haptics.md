---
layout: page
title: Northwestern Haptics Lab
permalink: /engineering/haptics
---

This project focuses on achieving high gain bilateral feedback control for a robotic glove and hand, meaning that the robot hand will mimick your hand and you will feel forces the robot feels. 
This project was commissioned by the Department of Energy so that researchers can remotely do dexterous tasks to avoid severe radiation exposure. 
The first 6 months of the project were for creating an alpha prototype as a capstone project. 
In the second iteration, we focused on optimizing for manufacturability, reliability, and further mimicking human hand proportions. This project is ongoing and is pretty awesome. 

# Iteration 1: First Hand Experience

The overall team was 20 people. I was in the 5 person haptic finger subteam. We created a 2 rotational joint robot that fit over the wearer's index finger. 
This required understanding the hand very well. We began by investigating the form factor and user comfort through literature review, concept sketches, and low-fidelity prototypes.

<p float="left">
  <img src="/assets/img/haptics/sketch1.jpg" width="300" />
  <img src="/assets/img/haptics/sketch2.JPG" width="300" />
  <img src="/assets/img/haptics/v1.JPG" width="300" /> 
</p>


We decided to use a cable transmission ratio since it was low friction and had no backlash (as opposed to gears which have backlash). 
We quickly learned that although this worked very well when set up properly, setting it up properly was pretty difficult. Over several iterations, we designed the system to have accessible and intuitive tensioning mechanisms. Cable slacking and slipping were our biggest enemies because it broke user immersion, desyncing between the haptic and robotic side, and could lead to further unravelling. 

<p float="left">
  <img src="/assets/img/haptics/route.png" width="600" />
  <img src="/assets/img/haptics/v2.jpg" width="300" />
</p>

We were successfully able to achieve bilateral control to complete lab tasks like unscrewing a water bottle or grasping a vial. 

<video controls width="960" height="540" muted loop autoplay>
    <source src="/assets/img/haptics/vid2.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>  

# Iteration 2: Triple Digits

<p float="left">
  <img src="/assets/img/haptics/aiet.png" width="600" />
</p>

Now that we learned what it took to carry out this design, we emphasized designing for ease of assembly and shrinking the design to a human form factor. We also decided to include a middle finger to make certain tasks easier. Other new features include potentiometers for joint position tracking, frameless motors to reduce weight, and an additional joint for finger splaying action. 



