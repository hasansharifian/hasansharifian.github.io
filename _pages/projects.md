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
    align-items: center;
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
    font-size: 1rem;
    line-height: 1.85;
    color: var(--global-text-color);
    margin: 0;
  }

  .project-visual {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .project-icon-wrap {
    width: 140px;
    height: 140px;
    border-radius: 20px;
    background: var(--global-code-bg-color, #f0f0f0);
    border: 1px solid var(--global-divider-color, #e0e0e0);
    display: flex;
    align-items: center;
    justify-content: center;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .project-entry:hover .project-icon-wrap {
    transform: scale(1.04);
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
  }

  .project-visual img {
    width: 100px;
    height: 100px;
    object-fit: contain;
    mix-blend-mode: multiply;
  }

  html[data-theme="dark"] .project-visual img,
  [data-bs-theme="dark"] .project-visual img {
    mix-blend-mode: normal;
    filter: brightness(1.1);
  }

  @media (max-width: 600px) {
    .project-entry {
      grid-template-columns: 1fr;
    }
    .project-visual {
      display: none;
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
      <div class="project-icon-wrap">
        <img src="{{ '/assets/icons/cognitive-style.png' | relative_url }}" alt="Cognitive Styles">
      </div>
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <div class="project-number">Project 02</div>
      <h3 class="project-title">Honor, Ideology, and Prejudice</h3>
      <p class="project-body">This project investigates whether honor values uniquely predict prejudice above and beyond established ideological orientations such as right-wing authoritarianism and social dominance orientation, across multiple target groups. Existing research offers mixed evidence on whether honor contributes independently to intergroup bias or merely overlaps with existing constructs. Using a combination of survey and experimental methods, this project disentangles the motivational foundations of honor, SDO, and RWA, and tests whether different target groups and threat types selectively activate these motives. The goal is to clarify when and why honor predicts prejudice, and to specify the conditions under which its effects diverge from broader ideological dispositions.</p>
    </div>
    <div class="project-visual">
      <div class="project-icon-wrap">
        <img src="{{ '/assets/icons/predictors-of-prejudice.png' | relative_url }}" alt="Honor, Ideology, and Prejudice">
      </div>
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <div class="project-number">Project 03</div>
      <h3 class="project-title">Cultural Variation in Conflict Strategy</h3>
      <p class="project-body">Why do some groups escalate conflicts mainly when they have the power to win, while others escalate even when the odds are against them? This question sits at the intersection of psychology and international relations, where competing theories emphasize instrumental calculations versus reputational concerns. Drawing on historical interstate disputes and large-scale behavioral data from Clash of Clans online videogame, this project examines how the balance between power and reputation in conflict escalation varies across cultures, and whether similar patterns emerge across international politics and virtual competition.</p>
    </div>
    <div class="project-visual">
      <div class="project-icon-wrap">
        <img src="{{ '/assets/icons/conflict-strategies.png' | relative_url }}" alt="Cultural Variation in Conflict Strategy">
      </div>
    </div>
  </div>

</div>
