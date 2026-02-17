---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
---

<div class="project-list">

  <div class="project-item">
    <div class="project-content">
      <h3>Cognitive Styles</h3>
      <p>A central framework in cultural psychology contrasts analytic and holistic cognition, largely derived from East Asian–Western comparisons. In this project, I examine how well this framework generalizes across additional cultural contexts using experimental tasks that tap visual attention, judgment of change, causal attribution, syllogistic reasoning, and item categorization. The aim is to assess when the analytic–holistic distinction extends beyond the West–East cultural boundaries.</p>
    </div>
    <img src="{{ '/assets/icons/cognitive-style.png' | relative_url }}" alt="Cognitive Styles" class="project-img">
  </div>

  <hr>

  <div class="project-item">
    <div class="project-content">
      <h3>Honor, Ideology, and Prejudice</h3>
      <p>This project investigates whether honor values uniquely predict prejudice above and beyond established ideological orientations such as right-wing authoritarianism and social dominance orientation, across multiple target groups. Existing research offers mixed evidence on whether honor contributes independently to intergroup bias or merely overlaps with existing constructs. Using a combination of survey and experimental methods, this project disentangles the motivational foundations of honor, SDO, and RWA, and tests whether different target groups and threat types selectively activate these motives. The goal is to clarify when and why honor predicts prejudice, and to specify the conditions under which its effects diverge from broader ideological dispositions.</p>
    </div>
    <img src="{{ '/assets/icons/predictors-of-prejudice.png' | relative_url }}" alt="Honor, Ideology, and Prejudice" class="project-img">
  </div>

  <hr>

  <div class="project-item">
    <div class="project-content">
      <h3>Cultural Variation in Conflict Strategy</h3>
      <p>Why do some groups escalate conflicts mainly when they have the power to win, while others escalate even when the odds are against them? This question sits at the intersection of psychology and international relations, where competing theories emphasize instrumental calculations versus reputational concerns. Drawing on historical interstate disputes and large-scale behavioral data from Clash of Clans online videogame, this project examines how the balance between power and reputation in conflict escalation varies across cultures, and whether similar patterns emerge across international politics and virtual competition.</p>
    </div>
    <img src="{{ '/assets/icons/conflict-strategies.png' | relative_url }}" alt="Cultural Variation in Conflict Strategy" class="project-img">
  </div>

</div>

<style>
  .project-list {
    margin-top: 1rem;
  }
  .project-item {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    padding: 1.5rem 0;
  }
  .project-content {
    flex: 1;
  }
  .project-content h3 {
    margin-top: 0;
    margin-bottom: 0.5rem;
  }
  .project-content p {
    margin: 0;
    line-height: 1.7;
    color: var(--global-text-color);
  }
  .project-img {
    width: 90px;
    height: 90px;
    object-fit: contain;
    flex-shrink: 0;
    opacity: 0.85;
  }
  hr {
    border: none;
    border-top: 1px solid var(--global-divider-color, #e0e0e0);
    margin: 0;
  }
</style>
