---
title: 视频
date: 2025-06-20
layout: video-gallery
---

通过视频了解我们的机器人研究、会议展示与田间试验。

---

<div class="video-grid">

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video1" class="video-popup">
      <img src="https://img.youtube.com/vi/qBgaOyAfMuU/maxresdefault.jpg" alt="草莓采摘机器人">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>草莓采摘机器人</h3>
    <p class="video-meta">田间试验 · 2024年5月 · 2:15</p>
    <p>在商业温室中开展自主采摘，实现果实实时识别与轻柔抓取。</p>
  </div>
</div>

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video2" class="video-popup">
      <img src="https://img.youtube.com/vi/8LFWqqUss18/maxresdefault.jpg" alt="激光除草机器人">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>激光除草机器人 WeedHitter</h3>
    <p class="video-meta">精准农业 · 2025年3月 · 4:30</p>
    <p>采用误差补偿轨迹与人工智能杂草识别的高精度激光除草系统。</p>
  </div>
</div>

<div class="video-card">
  <div class="video-thumbnail">
    <a href="#video3" class="video-popup">
      <img src="https://img.youtube.com/vi/HQ6BfMei63I/maxresdefault.jpg" alt="定向授粉机器人">
      <div class="play-button">▶</div>
    </a>
  </div>
  <div class="video-info">
    <h3>定向授粉机器人</h3>
    <p class="video-meta">精准农业 · 2025年3月 · 4:30</p>
    <p>多机械臂产生多方向气流振动，实现面向花朵的定向授粉。</p>
  </div>
</div>

</div>

<div id="video1" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container"><iframe src="https://www.youtube.com/embed/qBgaOyAfMuU" frameborder="0" allowfullscreen></iframe></div>
    <div class="video-modal-info"><h4>草莓采摘机器人</h4><p>视频展示第二代草莓采摘机器人在商业温室中的作业过程。</p></div>
  </div>
</div>

<div id="video2" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container"><iframe src="https://www.youtube.com/embed/8LFWqqUss18" frameborder="0" allowfullscreen></iframe></div>
    <div class="video-modal-info"><h4>激光除草机器人 WeedHitter</h4><p>展示采用误差补偿技术的精准激光除草系统。</p></div>
  </div>
</div>

<div id="video3" class="video-modal">
  <div class="modal-content">
    <a href="#" class="close-modal">&times;</a>
    <div class="video-container"><iframe src="https://www.youtube.com/embed/HQ6BfMei63I" frameborder="0" allowfullscreen></iframe></div>
    <div class="video-modal-info"><h4>定向授粉机器人</h4><p>多机械臂利用多方向气流振动开展定向授粉。</p></div>
  </div>
</div>

<style>
.video-grid { display:grid; grid-template-columns:repeat(auto-fill,minmax(320px,1fr)); gap:2rem; margin:2rem 0; }
.video-card { background:#fff; border-radius:12px; overflow:hidden; box-shadow:0 4px 20px rgba(0,0,0,.08); transition:.3s; border:1px solid #eaeaea; }
.video-card:hover { transform:translateY(-8px); box-shadow:0 12px 30px rgba(0,0,0,.15); border-color:#4CAF50; }
.video-thumbnail { position:relative; padding-top:56.25%; overflow:hidden; background:#eef2f5; }
.video-thumbnail img { position:absolute; inset:0; width:100%; height:100%; object-fit:cover; transition:transform .5s; }
.video-card:hover .video-thumbnail img { transform:scale(1.05); }
.play-button { position:absolute; top:50%; left:50%; transform:translate(-50%,-50%); width:70px; height:70px; border-radius:50%; background:#d00; color:#fff; display:flex; align-items:center; justify-content:center; font-size:30px; opacity:0; transition:.3s; }
.video-thumbnail:hover .play-button { opacity:1; transform:translate(-50%,-50%) scale(1.1); }
.video-info { padding:1.5rem; }
.video-info h3 { margin:0 0 .5rem; color:#2c3e50; font-size:1.25rem; }
.video-meta { color:#666; font-size:.85rem; margin-bottom:1rem; }
.video-info p { color:#555; line-height:1.6; }
.video-modal { display:none; position:fixed; inset:0; background:rgba(0,0,0,.95); z-index:10000; align-items:center; justify-content:center; padding:20px; }
.video-modal:target { display:flex; }
.modal-content { position:relative; width:95%; max-width:1000px; background:#1a1a1a; border-radius:12px; overflow:hidden; }
.close-modal { position:absolute; top:15px; right:20px; z-index:100; color:#fff; font-size:32px; text-decoration:none; }
.video-container { position:relative; padding-top:56.25%; background:#000; }
.video-container iframe { position:absolute; inset:0; width:100%; height:100%; border:0; }
.video-modal-info { padding:2rem; background:#fff; }
.video-modal-info h4 { margin:0 0 1rem; color:#2c3e50; font-size:1.5rem; }
.video-modal-info p { color:#555; line-height:1.7; }
@media (max-width:768px) { .video-grid { grid-template-columns:1fr; gap:1.5rem; } .modal-content { width:98%; } }
</style>
