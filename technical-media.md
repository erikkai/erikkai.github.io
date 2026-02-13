---
layout: default
title: Technical Media
has_children: true
has_toc: false
nav_order: 4
---

<style>
  .media-grid {
    display: grid;
    /* Adjusted minmax to 320px to prevent squishing on medium screens */
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 30px;
    margin-top: 40px;
  }
  .video-container {
    background: #161616;
    border: 1px solid #333;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.2s ease;
    display: flex;
    flex-direction: column;
  }
  .video-container:hover { transform: translateY(-5px); }
  .video-wrapper {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
  }
  .video-wrapper iframe {
    position: absolute;
    top: 0; left: 0; width: 100%; height: 100%;
    border: 0;
  }
  .video-info { padding: 20px; flex-grow: 1; }
  .video-label { color: #00d2ff; font-size: 0.75rem; text-transform: uppercase; letter-spacing: 1px; font-weight: bold; }
  .video-title { color: #fff; font-size: 1.1rem; margin: 8px 0; font-weight: 600; }
  .video-desc { color: #888; font-size: 0.85rem; line-height: 1.5; }
</style>

# Technical Media & Documentation

<p style="color: #aaa; max-width: 800px;">
  Deep-dive technical walkthroughs and engineering fundamentals for the api.video ecosystem, focusing on Python integration, authentication flows, and video compression theory.
</p>

<div class="media-grid">

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/DakHAB5PYWA" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Video Theory</div>
      <h3 class="video-title">What is Chroma Subsampling?</h3>
      <p class="video-desc">An engineering-level breakdown of YCbCr color spaces and how throwing away color data optimizes compression without sacrificing human-perceived quality.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/x5o2BydRb0c" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Full-Stack Implementation</div>
      <h3 class="video-title">Upload Videos with Flask, Dropzone, and Python</h3>
      <p class="video-desc">A comprehensive 11-minute guide on handling multi-part form data and chunked large-file uploads using the api.video Python client.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/QE-omRwT1AI" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Fundamentals</div>
      <h3 class="video-title">What is Bit Depth?</h3>
      <p class="video-desc">Explaining the relationship between color depth, banding, and storage requirements for 8-bit vs 24-bit digital video representations.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/F7xKn92r_0Y" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Security & Auth</div>
      <h3 class="video-title">Python: Refreshing Access Tokens</h3>
      <p class="video-desc">Technical walkthrough on how to work with access and refresh tokens for api.video without using the standard client.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/H5GcG3EP8Kc" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">API Features</div>
      <h3 class="video-title">Dynamic Thumbnail Management</h3>
      <p class="video-desc">Demonstrating programmatic thumbnail assignment via the api.video Python client, including JPEG uploads and time-code frame extraction.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/TUGCqs2mmAc" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Ingestion Workflows</div>
      <h3 class="video-title">Upload from a Public URL</h3>
      <p class="video-desc">Demonstrating how to bypass local containers by using the source parameter to ingest videos directly from public-facing URLs via Python.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/33phbsxlHJw" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Security</div>
      <h3 class="video-title">Authentication & Bearer Tokens</h3>
      <p class="video-desc">A look at exchanging API keys for bearer tokens and implementing delegated uploads for secure client-side interactions.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/4kWwSvrLtCA" allowfullscreen></iframe>
    </div>
    <div class="video-info">
      <div class="video-label">Client SDKs</div>
      <h3 class="video-title">Python Client: Local File Uploads</h3>
      <p class="video-desc">Step-by-step guide on initializing the Python client and managing local file ingestion to the api.video cloud.</p>
    </div>
  </div>

</div> 