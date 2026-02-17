---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
---

<style>
  .section {
    margin-bottom: 2rem;
  }

  .project-row {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 1.5rem;
    padding: 1rem 0;
    border-bottom: 1px solid #eee;
  }

  .project-text {
    flex: 1;
  }

  .project-title {
    background: none;
    border: none;
    padding: 0;
    font-size: 1.1rem;
    font-weight: 500;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    color: inherit;
    text-align: left;
  }

  .project-title:hover {
    color: var(--global-theme-color, #0076df);
  }

  .chevron::before {
    content: '▶';
    font-size: 0.65rem;
    display: inline-block;
    transition: transform 0.2s ease;
  }

  .project-row.open .chevron::before {
    transform: rotate(90deg);
  }

  .project-description {
    display: none;
    margin-top: 0.75rem;
    color: #444;
    line-height: 1.6;
  }

  .project-row.open .project-description {
    display: block;
  }

  .project-icon {
    width: 80px;
    height: 80px;
    object-fit: contain;
    flex-shrink: 0;
  }
</style>

<div class="section">
  <div class="project-row clickable">
    <div class="project-text">
      <button class="project-title">
        <span class="chevron"></span>
        Cognitive Styles
      </button>
      <div class="project-description">
        <p>
          A central framework in cultural psychology contrasts analytic and holistic cognition, largely derived from East Asian–Western comparisons. In this project, I examine how well this framework generalizes across additional cultural contexts using experimental tasks that tap visual attention, judgment of change, causal attribution, syllogistic reasoning, and item categorization. The aim is to assess when the analytic–holistic distinction extends beyond the West–East cultural boundaries.
        </p>
      </div>
    </div>
    <img src="{{ '/assets/icons/cognitive-style.png' | relative_url }}" class="project-icon" alt="Cognitive Styles">
  </div>
</div>

<div class="section">
  <div class="project-row clickable">
    <div class="project-text">
      <button class="project-title">
        <span class="chevron"></span>
        Honor, Ideology, and Prejudice
      </button>
      <div class="project-description">
        <p>
          This project investigates whether honor values uniquely predict prejudice above and beyond established ideological orientations such as right-wing authoritarianism and social dominance orientation, across multiple target groups. Existing research offers mixed evidence on whether honor contributes independently to intergroup bias or merely overlaps with existing constructs. Using a combination of survey and experimental methods, this project disentangles the motivational foundations of honor, SDO, and RWA, and tests whether different target groups and threat types selectively activate these motives. The goal is to clarify when and why honor predicts prejudice, and to specify the conditions under which its effects diverge from broader ideological dispositions.
        </p>
      </div>
    </div>
    <img src="{{ '/assets/icons/predictors-of-prejudice.png' | relative_url }}" class="project-icon" alt="Honor, Ideology, and Prejudice">
  </div>

  <div class="project-row clickable">
    <div class="project-text">
      <button class="project-title">
        <span class="chevron"></span>
        Cultural Variation in Conflict Strategy
      </button>
      <div class="project-description">
        <p>
          Why do some groups escalate conflicts mainly when they have the power to win, while others escalate even when the odds are against them? This question sits at the intersection of psychology and international relations, where competing theories emphasize instrumental calculations versus reputational concerns. Drawing on historical interstate disputes and large-scale behavioral data from Clash of Clans online videogame, this project examines how the balance between power and reputation in conflict escalation varies across cultures, and whether similar patterns emerge across international politics and virtual competition.
        </p>
      </div>
    </div>
    <img src="{{ '/assets/icons/conflict-strategies.png' | relative_url }}" class="project-icon" alt="Cultural Variation in Conflict Strategy">
  </div>
</div>

<script>
  document.querySelectorAll('.project-row.clickable').forEach(function(row) {
    row.querySelector('.project-title').addEventListener('click', function() {
      row.classList.toggle('open');
    });
  });
</script>
