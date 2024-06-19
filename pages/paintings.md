---
layout: page
title: Paintings
permalink: /arts/paintings
---

I work primarily with oil paints, and I enjoy surrealism and landscapes. 
Some of my biggest inspirations are [Simon Stalenhag](https://www.simonstalenhag.se/index.html), 
[Peter Schouten](https://en.wikipedia.org/wiki/Peter_Schouten), and [Mark Maggiori](https://markmaggiori.com/).

<style>
.container {
  display: block; /* Ensure the container stacks images vertically */
}

.image-card {
  position: relative;
  width: 100%; /* Make each card take full width */
  overflow: hidden;
  margin-bottom: 20px; /* Add space between images */
  transition: transform 0.3s ease;
}

.image-card img {
  width: 100%;
  display: block;
  transition: transform 0.3s ease;
}

.image-card:hover img {
  transform: scale(1.1);
}

.image-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.image-card:hover .image-overlay {
  opacity: 1;
}

.image-overlay p {
  font-size: 18px;
  font-weight: bold;
  text-align: center;
  margin: 10px;
}
</style>

<div class="container">
  <div class="image-card">
    <a href="/assets/img/paintings/dandelion.JPG" target="_blank">
      <img src="/assets/img/paintings/dandelion.JPG" alt="Dandelions">
      <div class="image-overlay">
        <p>Dandelions</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/paintings/joseph_sweeney.png" target="_blank">
      <img src="/assets/img/paintings/joseph_sweeney.png" alt="Joseph Sweeney through Gamsol">
      <div class="image-overlay">
        <p>Joseph Sweeney through Gamsol</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/sun-painting.JPG" target="_blank">
      <img src="/assets/img/sun-painting.JPG" alt="Sunny">
      <div class="image-overlay">
        <p>Sunny</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/paintings/dino.JPG" target="_blank">
      <img src="/assets/img/paintings/dino.JPG" alt="Dino, 5'x4'">
      <div class="image-overlay">
        <p>Dino, 5'x4'</p>
      </div>
    </a>
  </div>
</div>
