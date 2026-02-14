---
layout: default
title: Home
nav_order: 1
description: "Erikka Innes: Technical Storytelling and Engineering Portfolio"
---

<div class="py-6 px-6 mb-6" style="
  border-radius: 12px; 
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('/assets/images/tech-banner.jpg'); 
  background-size: cover; 
  background-position: center;
  color: white;
  border: 1px solid #333;">
  <h1 class="fs-9 text-white">Erikka Innes</h1>
  <p class="fs-6 fw-300">Technical Storytelling & Engineering Portfolio</p>
</div>

<div class="dashboard-grid">
  <a href="/engineering" class="card-link">
    <img src="/assets/images/engineering-code.webp" alt="Engineering and Code">
  </a>
  <a href="/case-studies" class="card-link">
    <img src="/assets/images/case-studies.webp" alt="Case Studies">
  </a>
  <a href="/technical-media" class="card-link">
    <img src="/assets/images/technical-media.webp" alt="Technical Media">
  </a>
  <a href="/strategic-positioning" class="card-link">
    <img src="/assets/images/strategy.webp" alt="Strategic Content and Product Positioning">
  </a>
  <a href="#creative" class="card-link">
    <img src="/assets/images/creative-lab.webp" alt="Creative Lab">
  </a>

</div>

<footer class="site-footer">
  <div class="footer-icons">
    <a href="https://github.com/erikkai" target="_blank" aria-label="GitHub">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" alt="GitHub" class="footer-icon">
    </a>
    <a href="https://erikka-innes.medium.com/" target="_blank" aria-label="Medium">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/medium.svg" alt="Medium" class="footer-icon">
    </a>
    <a href="https://www.youtube.com/@innes-tech" target="_blank" aria-label="YouTube">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/youtube.svg" alt="YouTube" class="footer-icon">
    </a>
    <a href="https://open.spotify.com/user/your-id" target="_blank" aria-label="Spotify">
      <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/spotify.svg" alt="Spotify" class="footer-icon">
    </a>
  </div>
  <p class="footer-text">© 2026 Erikka Innes | Engineering and Technical Storytelling</p>
</footer>

<style>
/* DASHBOARD STYLES */
.dashboard-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  padding: 2rem 0;
  max-width: 1200px;
  margin: 0 auto;
}

.card-link {
  text-decoration: none;
  perspective: 1000px;
  display: block;
  overflow: hidden;
  border-radius: 15px;
  background: #000;
  height: 350px; /* Locks the height so the watermark crop is consistent */
}

.card-link img {
  width: 100%;
  height: 125%; /* Pushes watermark out */
  object-fit: cover;
  object-position: top;
  transition: transform 0.4s ease;
  display: block;
}

.card-link:hover img {
  transform: scale(1.02) translateY(-2%); /* Subtle lift instead of large scale to protect the crop */
}

/* FOOTER STYLES */
.site-footer {
  text-align: center;
  padding: 3rem 0;
  border-top: 1px solid #333;
  margin-top: 4rem;
}

.footer-icons {
  display: flex; /* This puts icons in a row */
  justify-content: center;
  gap: 30px;
  margin-bottom: 1.5rem;
}

.footer-icon {
  width: 28px; /* Forces icons to be small */
  height: 28px;
  filter: invert(1); /* Makes them white */
  transition: transform 0.3s ease, filter 0.3s ease;
}

.footer-icon:hover {
  transform: translateY(-5px);
  filter: invert(1) drop-shadow(0 0 8px #00d2ff);
}

.footer-text {
  color: #888;
  font-size: 0.9rem;
}
</style>