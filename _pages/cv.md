---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: false
classes: wide
---

<div class="research-cv">

  <!-- Header -->
  <div class="rcv-header">
    <h1>MD Azizul Hakim</h1>
    <p class="rcv-tagline">
      AI Researcher — Large Language Models, Inference Efficiency, Alignment
    </p>

    <div class="rcv-links">
      <a href="https://scholar.google.com/citations?user=jVyIovcAAAAJ&hl=en" target="_blank">Google Scholar</a>
      <span>·</span>
      <a href="https://github.com/logicsame" target="_blank">GitHub</a>
      <span>·</span>
      <a href="https://www.linkedin.com/in/md-azizul-hakim-0b2635359/" target="_blank">LinkedIn</a>
      <span>·</span>
      <a href="mailto:azizulhakim8291@gmail.com">Email</a>
    </div>
  </div>

  <!-- Actions -->
  <div class="rcv-actions">
    <a href="/assets/resume.pdf" target="_blank" class="rcv-btn primary">
  📄 View CV
    </a>
    <a href="/assets/resume.pdf" download class="rcv-btn">
      ⬇ Download PDF
    </a>
  </div>

  <!-- Preview -->
  <div class="rcv-preview">
    <iframe src="/assets/files/cv.pdf"></iframe>
  </div>

</div>

<style>
.research-cv {
  max-width: 900px;
  margin: 0 auto;
  padding: 60px 20px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  color: #111;
}

/* Header */
.rcv-header {
  text-align: center;
  margin-bottom: 40px;
}

.rcv-header h1 {
  font-size: 2.6rem;
  font-weight: 600;
  margin-bottom: 8px;
  letter-spacing: -0.02em;
}

.rcv-tagline {
  font-size: 1.05rem;
  color: #555;
  margin-bottom: 18px;
}

/* Links */
.rcv-links {
  font-size: 0.95rem;
  color: #444;
}

.rcv-links a {
  color: #111;
  text-decoration: none;
  margin: 0 6px;
}

.rcv-links a:hover {
  text-decoration: underline;
}

/* Buttons */
.rcv-actions {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-bottom: 40px;
}

.rcv-btn {
  padding: 10px 20px;
  border: 1px solid #ddd;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.95rem;
  color: #111;
  transition: all 0.2s ease;
}

.rcv-btn:hover {
  background: #f5f5f5;
}

.rcv-btn.primary {
  background: #111;
  color: white;
  border: none;
}

.rcv-btn.primary:hover {
  background: #333;
}

/* Preview */
.rcv-preview {
  width: 100%;
  height: 900px;
  border: 1px solid #eee;
  border-radius: 8px;
  overflow: hidden;
}

.rcv-preview iframe {
  width: 100%;
  height: 100%;
  border: none;
}

/* Mobile */
@media (max-width: 768px) {
  .rcv-preview {
    height: 600px;
  }

  .rcv-header h1 {
    font-size: 2rem;
  }
}
</style>
