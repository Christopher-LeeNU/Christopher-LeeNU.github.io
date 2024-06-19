---
layout: page
title: Paleoart
permalink: /arts/paleoart
---

These are my entries for the 2020 Dinovember challenge hosted by Charlotte Hohman. I based my drawings on fossils, descriptions in papers, and I chose plants based on what may have been living in the area at the time. Color patterns are speculative.  

<style>
.image-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.image-card {
  position: relative;
  width: 500px;
  overflow: hidden;
  transition: transform 0.3s ease;
}

.image-card img {
  width: 100%;
  display: block;
  transition: transform 0.3s ease;
  border-radius: 5px;
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

<div class="image-container">
  <div class="image-card">
    <a href="/assets/img/dromornis.jpg" target="_blank">
      <img src="/assets/img/dromornis.jpg" alt="Dromornis">
      <div class="image-overlay">
        <p>Dromornis</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/Dinovember2020/chenanisaurus.jpg" target="_blank">
      <img src="/assets/img/Dinovember2020/chenanisaurus.jpg" alt="Chenanisaurus">
      <div class="image-overlay">
        <p>Chenanisaurus</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/Dinovember2020/zuniceratops.jpg" target="_blank">
      <img src="/assets/img/Dinovember2020/zuniceratops.jpg" alt="Zuniceratops">
      <div class="image-overlay">
        <p>Zuniceratops</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/Dinovember2020/einiosaurus.jpg" target="_blank">
      <img src="/assets/img/Dinovember2020/einiosaurus.jpg" alt="Einiosaurus">
      <div class="image-overlay">
        <p>Einiosaurus</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/Dinovember2020/pelagornis.jpg" target="_blank">
      <img src="/assets/img/Dinovember2020/pelagornis.jpg" alt="Pelagornis">
      <div class="image-overlay">
        <p>Pelagornis</p>
      </div>
    </a>
  </div>
  
  <div class="image-card">
    <a href="/assets/img/Dinovember2020/velafronstree.jpg" target="_blank">
      <img src="/assets/img/Dinovember2020/velafronstree.jpg" alt="Velafrons">
      <div class="image-overlay">
        <p>Velafrons</p>
      </div>
    </a>
  </div>
</div>
