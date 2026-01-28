---
title: "Video Gallery"
date: 2025-06-20
layout: video-gallery
---

# S-H Robotics Lab Video Gallery

Explore our robotics research through video demonstrations, conference presentations, and field tests.

---

<div class="video-grid">

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video1" class="video-popup">
      <img src="https://img.youtube.com/vi/qBgaOyAfMuU/maxresdefault.jpg" alt="Strawberry Harvesting Robot">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>Strawberry Harvesting Robot</h3>
    <p class="video-meta">Field Test • May 2024 • 2:15</p>
    <p>Autonomous harvesting in commercial greenhouse with real-time fruit detection.</p>
  </div>
</div>

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video2" class="video-popup">
      <img src="https://img.youtube.com/vi/9b35prCKhio/maxresdefault.jpg" alt="Laser Weeding Robot">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>Laser Weeding Robot</h3>
    <p class="video-meta">Precision Agriculture • April 2024 • 3:42</p>
    <p>AI-based weed detection with millimeter-level targeting accuracy.</p>
  </div>
</div>

</div>

<!-- Video Modals -->
<div id="video1" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/qBgaOyAfMuU" frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</div>

<div id="video2" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/9b35prCKhio" frameborder="0" allowfullscreen></iframe>
    </div>
  </div>
</div>

<style>
/* Video Grid Layout */
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.video-card {
  background: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 3px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.video-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 20px rgba(0,0,0,0.15);
}

.video-thumbnail {
  position: relative;
  padding-top: 56.25%; /* 16:9 aspect ratio */
  background: #000;
  overflow: hidden;
}

.video-thumbnail img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.video-thumbnail .play-button {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 70px;
  height: 70px;
  background: rgba(255, 0, 0, 0.8);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 30px;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.video-thumbnail:hover .play-button {
  opacity: 1;
}

.video-info {
  padding: 1.5rem;
}

.video-info h3 {
  margin: 0 0 0.5rem 0;
  color: #2c3e50;
  font-size: 1.2rem;
}

.video-meta {
  color: #666;
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

.video-info p {
  color: #444;
  line-height: 1.5;
  margin: 0;
}

/* Video Modal Styles */
.video-modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.9);
  z-index: 1000;
  align-items: center;
  justify-content: center;
}

.video-modal:target {
  display: flex;
}

.modal-content {
  position: relative;
  width: 90%;
  max-width: 900px;
  background: black;
  border-radius: 5px;
  overflow: hidden;
}

.close-modal {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 28px;
  text-decoration: none;
  z-index: 10;
  background: rgba(0,0,0,0.5);
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.video-container {
  position: relative;
  padding-top: 56.25%; /* 16:9 aspect ratio */
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  .video-grid {
    grid-template-columns: 1fr;
  }
  
  .modal-content {
    width: 95%;
  }
}
</style>