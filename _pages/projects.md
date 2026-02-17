---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
---

<style>
  .project-entry {
    display: grid;
    grid-template-columns: 1fr 160px;
    gap: 2.5rem;
    padding: 2.8rem 0;
    border-bottom: 1px solid var(--global-divider-color, #e8e8e8);
    align-items: start;
  }

  .project-entry:first-child {
    padding-top: 0.5rem;
  }

  .project-entry:last-child {
    border-bottom: none;
  }

  .project-number {
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--global-theme-color);
    margin-bottom: 0.5rem;
  }

  .project-title {
    font-size: 1.25rem;
    font-weight: 700;
    margin: 0 0 0.9rem 0;
    color: var(--global-text-color);
    line-height: 1.3;
  }

  .project-body {
    text-align: justify;
    font-size: 1rem;
    line-height: 1.85;
    color: var(--global-text-color);
    margin: 0;
  }

  .project-visual {
    align-self: start;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  /* Only apply the offset on desktop where the image is visible */
  @media (min-width: 601px) {
    .project-visual {
      margin-top: 3.2rem;
    }
  }

  .project-visual img {
    width: 200px;
    height: 200px;
    object-fit: contain;
    /* Invert dark icons for light mode so they become light and visible */
    filter: invert(1);
    transition: transform 0.3s, opacity 0.3s;
    opacity: 0.85;
  }

  /* In dark mode, icons are already light — no inversion needed */
  html[data-theme="dark"] .project-visual img,
  [data-bs-theme="dark"] .project-visual img {
    filter: invert(0);
    opacity: 1;
  }

  .project-entry:hover .project-visual img {
    transform: scale(1.06);
    opacity: 1;
  }

  @media (max-width: 600px) {
    .project-entry {
      grid-template-columns: 1fr;
    }
    .project-visual {
      display: flex;
      justify-content: center;
      margin-top: 1.5rem;
    }
    .project-visual img {
      width: 90px;
      height: 90px;
    }
  }
</style>

<div class="projects-list">

  <div class="project-entry">
    <div class="project-text">
      <div class="project-number">Project 01</div>
      <h3 class="project-title">Cognitive Styles</h3>
      <p class="project-body">A central framework in cultural psychology contrasts analytic and holistic cognition, largely derived from East Asian–Western comparisons. In this project, I examine how well this framework generalizes across additional cultural contexts using experimental tasks that tap visual attention, judgment of change, causal attribution, syllogistic reasoning, and item categorization. The aim is to assess when the analytic–holistic distinction extends beyond the West–East cultural boundaries.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/cognitive-style.png' | relative_url }}" alt="Cognitive Styles">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <div class="project-number">Project 02</div>
      <h3 class="project-title">Honor, Ideology, and Prejudice</h3>
      <p class="project-body">This project investigates whether honor values uniquely predict prejudice above and beyond established ideological orientations such as right-wing authoritarianism and social dominance orientation, across multiple target groups. Existing research offers mixed evidence on whether honor contributes independently to intergroup bias or merely overlaps with existing constructs. Using a combination of survey and experimental methods, this project disentangles the motivational foundations of honor, SDO, and RWA, and tests whether different target groups and threat types selectively activate these motives. The goal is to clarify when and why honor predicts prejudice, and to specify the conditions under which its effects diverge from broader ideological dispositions.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/predictors-of-prejudice.png' | relative_url }}" alt="Honor, Ideology, and Prejudice">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <div class="project-number">Project 03</div>
      <h3 class="project-title">Cultural Variation in Conflict Strategy</h3>
      <p class="project-body">Why do some groups escalate conflicts mainly when they have the power to win, while others escalate even when the odds are against them? This question sits at the intersection of psychology and international relations, where competing theories emphasize instrumental calculations versus reputational concerns. Drawing on historical interstate disputes and large-scale behavioral data from Clash of Clans online videogame, this project examines how the balance between power and reputation in conflict escalation varies across cultures, and whether similar patterns emerge across international politics and virtual competition.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/conflict-strategies.png' | relative_url }}" alt="Cultural Variation in Conflict Strategy">
    </div>
  </div>

</div>

<div class="contact-footer">
  <div>Department of Psychology, University of Michigan</div>
  <div>
    <a href="https://maps.google.com/?q=530+Church+Street,+Ann+Arbor,+MI+48109" target="_blank" rel="noopener">
      530 Church Street, Ann Arbor, MI 48109
    </a>
  </div>
  <div>
    <a href="mailto:sharifih@umich.edu">sharifih@umich.edu</a>
    &nbsp;·&nbsp;
    <a href="mailto:hasan_sharifian@yahoo.com">hasan_sharifian@yahoo.com</a>
  </div>
</div>

<style>
  .contact-footer {
    margin-top: 3rem;
    padding-top: 1.5rem;
    border-top: 1px solid var(--global-divider-color, #e8e8e8);
    font-size: 0.9rem;
    line-height: 2;
    color: var(--global-text-color-light, #888);
    text-align: center;
  }

  .contact-footer a {
    color: var(--global-text-color-light, #888);
    text-decoration: none;
  }

  .contact-footer a:hover {
    color: var(--global-theme-color);
  }
</style>
