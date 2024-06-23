---
layout: post
title: "Engineering"
author: "Chris Lee"
permalink: /engineering
categories: documentation
tags: [documentation,sample]
image: cuba-1.jpg
---

I realized I loved engineering after competing in FIRST robotics throughout highschool. I have skills ranging from manufacturing, robotics, machine learning, and embedded systems. Check out what I made below!

<style>
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.image-card {
  position: relative;
  width: 300px;
  margin: 20px;
  overflow: hidden;
  transition: transform 0.3s ease;
}

.image-card img {
  width: 100%;
  display: block;
  transition: transform 0.3s ease;
}

.image-card:hover {
  transform: scale(1.05);
}

.image-card:hover img {
  transform: scale(1.1);
}

.overlay {
  position: absolute;
  bottom: 0;
  background: rgba(0, 0, 0, 0.7);
  color: #fff;
  width: 100%;
  text-align: center;
  padding: 10px;
  transition: 0.3s ease;
  border-radius: 0; /* Ensure sharp corners */
}

.image-card:hover .overlay {
  bottom: 0;
}
</style>

<div class="container">
  <div class="image-card">
    <a href="/engineering/haptics">
      <img src="/assets/img/aiet-hand.png" alt="Northwestern Haptics Lab">
      <div class="overlay">Northwestern Haptics Lab</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/engineering/formula">
      <img src="/assets/img/upright.png" alt="Formula Racing">
      <div class="overlay">Formula Racing</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/engineering/DS">
      <img src="/assets/img/da-snake.jpg" alt="DS">
      <div class="overlay">DS (Da Snake)</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/engineering/kuka">
      <img src="/assets/img/kukapic.png" alt="KUKA youBot">
      <div class="overlay">KUKA youBot</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/engineering/belltrain">
      <img src="/assets/img/mykalebelltrain/belltrain.JPEG" alt="My Kale Bell Train">
      <div class="overlay">My Kale Bell Train</div>
    </a>
  </div>
</div>
