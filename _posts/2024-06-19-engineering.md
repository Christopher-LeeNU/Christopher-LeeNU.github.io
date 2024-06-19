---
layout: post
title: "Engineering"
author: "Chris Lee"
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
    <a href="/facts">
      <img src="/assets/img/raccoon.jpg" alt="Origami">
      <div class="overlay">Origami</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/facts">
      <img src="/assets/img/dromornis.jpg" alt="Paleoart">
      <div class="overlay">Paleoart</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/facts">
      <img src="/assets/img/sun-painting.JPG" alt="Painting">
      <div class="overlay">Painting</div>
    </a>
  </div>
</div>
