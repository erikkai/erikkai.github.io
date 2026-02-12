---
layout: default
title: Engineering & Code
nav_order: 2
---

<style>
  .project-entry {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    margin-bottom: 80px;
    align-items: flex-start;
  }
  .project-info {
    flex: 2;
    min-width: 300px;
  }
  .project-meta {
    flex: 1;
    min-width: 200px;
    background: #111;
    padding: 20px;
    border-radius: 12px;
    border: 1px solid #333;
  }
  .tag {
    display: inline-block;
    background: #222;
    color: #00d2ff;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 0.8rem;
    margin: 0 5px 10px 0;
    border: 1px solid #333;
  }
  h1 { border-bottom: 1px solid #333; padding-bottom: 20px; margin-bottom: 50px; }
  h3 { color: #fff; margin-top: 0; }
</style>

# Engineering & Code

<div class="project-entry">
  <div class="project-info">
    <h3>TT-XLA & JAX: Hardware Onboarding & Tutorials</h3>
    <p>Developed comprehensive technical onboarding documentation for the Tenstorrent TT-XLA compiler frontend. This project bridges the gap from local environment configuration (Docker/Source) to executing optimized JAX models on physical silicon, using data and tensor parallelism for multi-chip execution.</p>
    <a href="https://github.com/erikkai/tt-xla-jax-onboarding" target="_blank" style="color: #00d2ff;">View Repository →</a>
  </div>
  
  <div class="project-meta">
    <strong style="display:block; margin-bottom: 10px; font-size: 0.9rem;">TECH STACK</strong>
    <span class="tag">JAX</span>
    <span class="tag">TT-XLA</span>
    <span class="tag">Python</span>
    <span class="tag">Docker</span>
  </div>
</div>

<div class="project-entry">
  <div class="project-info">
    <h3>api.video Python Client</h3>
    <p>Authored developer code samples and contributed to the official Python SDK for api.video. The client streamlines video infrastructure management by automating complex tasks like chunked file uploads, pagination, and token refresh logic, enabling developers to integrate low-latency live streaming and VOD features quickly.</p>
    <a href="https://github.com/erikkai/api.video-python-client" target="_blank" style="color: #00d2ff;">View Repository →</a>
  </div>
  
  <div class="project-meta">
    <strong style="display:block; margin-bottom: 10px; font-size: 0.9rem;">TECH STACK</strong>
    <span class="tag">Python</span>
    <span class="tag">REST API</span>
    <span class="tag">OpenAPI</span>
    <span class="tag">SDK Development</span>
  </div>
</div>

<div class="project-entry">
  <div class="project-info">
    <h3>JWT Authentication Service</h3>
    <p>Architected a standalone JWT service for secure token-based authentication. The service integrates a Flask-based API with a MongoDB backend to generate, encode, and store session tokens associated with unique external IDs (XIDs), ensuring secure transaction tracking and verification flows.</p>
    <a href="https://github.com/erikkai/telesign-appverify-jwt-service" target="_blank" style="color: #00d2ff;">View Repository →</a>
  </div>
  
  <div class="project-meta">
    <strong style="display:block; margin-bottom: 10px; font-size: 0.9rem;">TECH STACK</strong>
    <span class="tag">Python</span>
    <span class="tag">Flask</span>
    <span class="tag">MongoDB</span>
    <span class="tag">JWT</span>
  </div>
</div>


<hr style="border: 0; border-top: 1px solid #333; margin: 60px 0;">
<h2 style="margin-bottom: 30px;">Other Projects</h2>

<div style="margin-bottom: 30px;">
  <h4 style="margin: 0;">Forge Doc Tester</h4>
  <a href="https://github.com/erikkai/forge_doc_tester" target="_blank" style="color: #00d2ff; font-size: 0.9rem; text-decoration: none;">View Repository →</a>
  <p style="margin: 5px 0; font-size: 0.95rem; color: #ccc;">An MVP for an automated testing utility designed to validate bash instructions / code snippets within documentation to ensure technical accuracy.</p>
</div>

<div style="margin-bottom: 30px;">
  <h4 style="margin: 0;">Using Flask with Dropzone</h4>
  <a href="https://github.com/erikkai/flask_and_dropzone" target="_blank" style="color: #00d2ff; font-size: 0.9rem; text-decoration: none;">View Repository →</a>
  <p style="margin: 5px 0; font-size: 0.95rem; color: #ccc;">A functional implementation of drag-and-drop file uploads using Flask and the Dropzone.js library. Built after noticing many developers struggled to combine the two in certain cases.</p>
</div>

<div style="margin-bottom: 30px;">
  <h4 style="margin: 0;">Detect Fraudulent Calls Using TeleSign's Voice and Score Products</h4>
  <a href="https://github.com/erikkai/voice_and_score" target="_blank" style="color: #00d2ff; font-size: 0.9rem; text-decoration: none;">View Repository →</a>
  <p style="margin: 5px 0; font-size: 0.95rem; color: #ccc;">A creative engineering project exploring the intersection of voice commands and real-time scoring mechanics. The project won a prize in our company hackathon.</p>
</div>

<div style="margin-bottom: 30px;">
  <h4 style="margin: 0;">Create an SMS Doorbell</h4>
  <a href="https://github.com/erikkai/sms_doorbell" target="_blank" style="color: #00d2ff; font-size: 0.9rem; text-decoration: none;">View Repository →</a>
  <p style="margin: 5px 0; font-size: 0.95rem; color: #ccc;">A hardware-software integration that triggers SMS notifications via API when a physical doorbell event is detected.</p>
</div>

<div style="margin-bottom: 30px;">
  <h4 style="margin: 0;">Swagger APIs for TeleSign's API Explorers</h4>
  <a href="https://github.com/erikkai/telesign_swagger" target="_blank" style="color: #00d2ff; font-size: 0.9rem; text-decoration: none;">View Repository →</a>
  <p style="margin: 5px 0; font-size: 0.95rem; color: #ccc;">The Swagger (now OpenAPI) files I put together from scratch to set up TeleSign's API explorers.</p>
</div>