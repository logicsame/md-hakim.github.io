---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
classes: wide
---

<div class="cv-page">

  <div class="cv-card">
    <h1>Curriculum Vitae</h1>
    <p class="cv-subtext">
      Download or preview my latest academic CV (updated May 2026)
    </p>

    <div class="cv-actions">
  <a href="https://github.com/logicsame/md-hakim.github.io/blob/master/assets/resume.pdf" target="_blank" class="cv-btn primary">
    📄 View CV
  </a>
  <a href="https://github.com/logicsame/md-hakim.github.io/blob/master/assets/resume.pdf" download class="cv-btn">
    ⬇ Download PDF
  </a>
</div>

<div class="cv-preview">
  <iframe src="/assets/resume.pdf"></iframe>
</div>

</div>

<style>
.cv-page {
  max-width: 1100px;
  margin: 0 auto;
  padding: 40px 20px;
}

/* Top Card */
.cv-card {
  text-align: center;
  margin-bottom: 40px;
}

.cv-card h1 {
  font-size: 2.6rem;
  color: #2a7ae2;
  margin-bottom: 10px;
}

.cv-subtext {
  color: #666;
  font-size: 1rem;
  margin-bottom: 25px;
}

/* Buttons */
.cv-actions {
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
}

.cv-btn {
  padding: 12px 26px;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.25s ease;
}

.cv-btn.primary {
  background: #2a7ae2;
  color: white;
}

.cv-btn.primary:hover {
  background: #1756a9;
}

.cv-btn.secondary {
  background: #f2f2f2;
  color: #333;
}

.cv-btn.secondary:hover {
  background: #e0e0e0;
}

/* PDF Preview */
.cv-preview {
  width: 100%;
  height: 900px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 8px 30px rgba(0,0,0,0.08);
  border: 1px solid #e6e6e6;
}

.cv-preview iframe {
  width: 100%;
  height: 100%;
  border: none;
}

/* Mobile */
@media (max-width: 768px) {
  .cv-preview {
    height: 600px;
  }

  .cv-card h1 {
    font-size: 2rem;
  }
}
</style>
