---
title: "Video Gallery"
date: 2025-06-20
layout: video-gallery
---

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
    <p>Autonomous harvesting in commercial greenhouse with real-time fruit detection and gentle picking mechanism.</p>
  </div>
</div>

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video2" class="video-popup">
      <img src="https://img.youtube.com/vi/8LFWqqUss18/maxresdefault.jpg" alt="Laser Weeding Robot">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>Laser Weeding Robot - WeedHitter</h3>
    <p class="video-meta">Precision Agriculture • March 2025 • 4:30</p>
    <p>High-precision CO₂ laser weeding system with error compensation trajectories and AI-based weed recognition.</p>
  </div>
</div>

<!-- Template for adding more videos -->
<div class="video-card template">
  <div class="video-thumbnail">
    <div class="add-video">
      <span>+</span>
      <p>Add New Video</p>
    </div>
  </div>
  <div class="video-info">
    <h3>Your Video Title</h3>
    <p class="video-meta">Category • Date • Duration</p>
    <p>Add description here.</p>
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
    <div class="video-modal-info">
      <h4>Strawberry Harvesting Robot</h4>
      <p>This video demonstrates our 3rd-generation strawberry harvesting robot operating in a commercial greenhouse.</p>
    </div>
  </div>
</div>

<div id="video2" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/8LFWqqUss18" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-modal-info">
      <h4>Laser Weeding Robot - WeedHitter</h4>
      <p>Demonstration of our precision laser weeding system with error compensation technology.</p>
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
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  border: 1px solid #eaeaea;
}

.video-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 30px rgba(0,0,0,0.15);
  border-color: #4CAF50;
}

.video-card.template {
  background: #f8f9fa;
  border: 2px dashed #ccc;
  cursor: pointer;
}

.video-card.template:hover {
  border-color: #4CAF50;
  background: #f0f7f0;
}

.video-thumbnail {
  position: relative;
  padding-top: 56.25%; /* 16:9 aspect ratio */
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  overflow: hidden;
}

.video-thumbnail img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.video-card:hover .video-thumbnail img {
  transform: scale(1.05);
}

.video-thumbnail .play-button {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 70px;
  height: 70px;
  background: linear-gradient(135deg, #FF0000, #CC0000);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 30px;
  opacity: 0;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(255, 0, 0, 0.3);
}

.video-thumbnail:hover .play-button {
  opacity: 1;
  transform: translate(-50%, -50%) scale(1.1);
}

.video-thumbnail .add-video {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #666;
}

.video-thumbnail .add-video span {
  font-size: 48px;
  font-weight: 300;
  display: block;
  margin-bottom: 10px;
  color: #4CAF50;
}

.video-info {
  padding: 1.5rem;
}

.video-info h3 {
  margin: 0 0 0.5rem 0;
  color: #2c3e50;
  font-size: 1.25rem;
  font-weight: 600;
  line-height: 1.3;
}

.video-meta {
  color: #666;
  font-size: 0.85rem;
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  gap: 8px;
}

.video-meta::before {
  content: "📅";
  font-size: 0.9rem;
}

.video-info p {
  color: #555;
  line-height: 1.6;
  margin: 0;
  font-size: 0.95rem;
}

/* Video Modal Styles */
.video-modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.95);
  z-index: 10000;
  align-items: center;
  justify-content: center;
  padding: 20px;
  animation: fadeIn 0.3s ease;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.video-modal:target {
  display: flex;
}

.modal-content {
  position: relative;
  width: 95%;
  max-width: 1000px;
  background: #1a1a1a;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 20px 60px rgba(0,0,0,0.3);
  animation: slideUp 0.4s ease;
}

@keyframes slideUp {
  from { transform: translateY(30px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}

.close-modal {
  position: absolute;
  top: 15px;
  right: 20px;
  color: white;
  font-size: 32px;
  text-decoration: none;
  z-index: 100;
  background: rgba(0,0,0,0.6);
  width: 45px;
  height: 45px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: all 0.3s ease;
  backdrop-filter: blur(5px);
}

.close-modal:hover {
  background: rgba(255, 0, 0, 0.8);
  transform: rotate(90deg);
}

.video-container {
  position: relative;
  padding-top: 56.25%; /* 16:9 aspect ratio */
  background: #000;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

.video-modal-info {
  padding: 2rem;
  background: #fff;
}

.video-modal-info h4 {
  margin: 0 0 1rem 0;
  color: #2c3e50;
  font-size: 1.5rem;
  font-weight: 600;
}

.video-modal-info p {
  color: #555;
  line-height: 1.7;
  margin-bottom: 1.5rem;
}

.video-modal-info ul {
  color: #555;
  line-height: 1.7;
  padding-left: 1.2rem;
  margin: 0;
}

.video-modal-info li {
  margin-bottom: 0.5rem;
}

.video-modal-info li:last-child {
  margin-bottom: 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  .video-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .modal-content {
    width: 98%;
  }
  
  .video-modal-info {
    padding: 1.5rem;
  }
  
  .video-info {
    padding: 1.2rem;
  }
  
  .video-info h3 {
    font-size: 1.1rem;
  }
}

@media (max-width: 480px) {
  .video-thumbnail .play-button {
    width: 60px;
    height: 60px;
    font-size: 24px;
  }
  
  .video-modal-info {
    padding: 1rem;
  }
  
  .close-modal {
    width: 40px;
    height: 40px;
    font-size: 28px;
  }
}
</style>

<script>
// Add interactive functionality
document.addEventListener('DOMContentLoaded', function() {
  // Close modal when clicking outside
  const modals = document.querySelectorAll('.video-modal');
  modals.forEach(modal => {
    modal.addEventListener('click', function(e) {
      if (e.target === this) {
        window.location.hash = '';
      }
    });
  });
  
  // Close modal with Escape key
  document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') {
      window.location.hash = '';
    }
  });
  
  // Template card click handler
  const templateCard = document.querySelector('.video-card.template');
  if (templateCard) {
    templateCard.addEventListener('click', function() {
      alert('To add a new video:\n1. Get YouTube video ID from URL\n2. Copy video-card template\n3. Update video ID and information\n4. Add corresponding modal section');
    });
  }
});
</script>