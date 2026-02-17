---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 3
---

<div class="cv-container">
  <div class="cv-actions">
    <a href="{{ '/assets/pdf/2025.12-CV.pdf' | relative_url }}" target="_blank" rel="noopener" class="cv-download">
      <i class="fa-solid fa-download"></i> Download PDF
    </a>
  </div>
  <iframe
    src="{{ '/assets/pdf/2025.12-CV.pdf' | relative_url }}"
    class="cv-frame"
    title="Curriculum Vitae">
  </iframe>
</div>

<style>
  .cv-container {
    margin-top: 1rem;
  }

  .cv-actions {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 0.75rem;
  }

  .cv-download {
    font-size: 0.85rem;
    color: var(--global-theme-color);
    text-decoration: none;
    border: 1px solid var(--global-theme-color);
    padding: 0.35rem 0.85rem;
    border-radius: 4px;
    transition: background 0.2s, color 0.2s;
  }

  .cv-download:hover {
    background: var(--global-theme-color);
    color: #fff;
  }

  .cv-frame {
    width: 100%;
    height: 85vh;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 4px;
  }

  @media (max-width: 600px) {
    .cv-frame {
      height: 70vh;
    }
  }
</style>
