---
layout: post
title: "Arts"
author: "Chris Lee"
categories: documentation
tags: [documentation, sample]
image: city-1.jpg
---

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
  border-radius: 10px;
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
}

.image-card:hover .overlay {
  bottom: 0;
}
</style>

<div class="container">
  <div class="image-card">
    <a href="/facts">
      <img src="/assets/img/racoon.jpg" alt="City">
      <div class="overlay">City Post</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/path/to/post2">
      <img src="/assets/img/nature-1.jpg" alt="Nature">
      <div class="overlay">Nature Post</div>
    </a>
  </div>
  <div class="image-card">
    <a href="/path/to/post3">
      <img src="/assets/img/abstract-1.jpg" alt="Abstract">
      <div class="overlay">Abstract Post</div>
    </a>
  </div>
</div>
