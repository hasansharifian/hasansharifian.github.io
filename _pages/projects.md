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
    grid-template-columns: minmax(0, 1fr) 180px;
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
    text-align: justify;
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

  .project-visual img {
    width: 180px;
    height: 180px;
    object-fit: contain;
    /* Most project icons have a dark source background. */
    filter: invert(1);
    transition: transform 0.3s, opacity 0.3s;
    opacity: 0.85;
  }

  /* The UN-speech artwork has a light source background. */
  .project-visual img.light-source-icon {
    filter: none;
  }

  html[data-theme="dark"] .project-visual img,
  [data-bs-theme="dark"] .project-visual img {
    filter: none;
    opacity: 1;
  }

  html[data-theme="dark"] .project-visual img.light-source-icon,
  [data-bs-theme="dark"] .project-visual img.light-source-icon {
    filter: invert(1);
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
      <h3 class="project-title">Cultural Variation in Conflict Strategy</h3>
      <p class="project-body">Why do some groups escalate conflicts mainly when they have the power to win, while others escalate even when the odds are against them? This question sits at the intersection of psychology and international relations, where competing theories emphasize instrumental calculations versus reputational concerns. Drawing on historical interstate disputes and large-scale behavioral data from Clash of Clans online videogame, this project examines how the balance between power and reputation in conflict escalation varies across cultures, and whether similar patterns emerge across international politics and virtual competition.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/conflict-strategies.png' | relative_url }}" alt="Cultural Variation in Conflict Strategy">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <h3 class="project-title">Honor and War: A Modeling Extension</h3>
      <p class="project-body">How does honor shape decisions about intergroup conflict? Honor has been argued to serve an evolutionary function, helping groups adapt to threats and survive in challenging environments. In this project, I use game theory and agent-based modeling to ask whether honor can play a functional role in international conflict as well. I incorporate honor into actors’ strategic calculations about whether to fight or back down, alongside material power, the stakes of conflict, and the costs of war. I then examine when sensitivity to honor helps actors survive, expand, or puts them at a disadvantage.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/ABM.png' | relative_url }}" alt="Honor and War: A Modeling Extension">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <h3 class="project-title">Human Values in Political Speech</h3>
      <p class="project-body">How are values expressed in political speeches? Previous studies have found links between values and foreign policy preferences at the individual level, but the extent to which world leaders’ policy positions reflect underlying values is less established. In this project, I use text analysis to identify, analyze, and compare Schwartz values in speeches given by world leaders at the United Nations General Assembly. More than eight decades of speeches from countries around the world provide a valuable resource for examining how human values vary across cultures and over time, and how they are associated with political outcomes.</p>
    </div>
    <div class="project-visual">
      <img class="light-source-icon" src="{{ '/assets/icons/human-values-political-speech.png' | relative_url }}" alt="Human Values in Political Speech">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <h3 class="project-title">Cognitive Styles</h3>
      <p class="project-body">A central framework in cultural psychology contrasts analytic and holistic cognition, largely derived from East Asian–Western comparisons. In this project, I examine how well this framework generalizes across additional cultural contexts using experimental tasks that tap visual attention, judgment of change, causal attribution, syllogistic reasoning, and item categorization. The aim is to assess when the analytic–holistic distinction extends beyond the West–East cultural boundaries.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/cognitive-style.png' | relative_url }}" alt="Cognitive Styles">
    </div>
  </div>

  <div class="project-entry">
    <div class="project-text">
      <h3 class="project-title">Honor, Ideology, and Prejudice</h3>
      <p class="project-body">This project investigates whether honor values uniquely predict prejudice above and beyond established ideological orientations such as right-wing authoritarianism and social dominance orientation, across multiple target groups. Existing research offers mixed evidence on whether honor contributes independently to intergroup bias or merely overlaps with existing constructs. Using a combination of survey and experimental methods, this project disentangles the motivational foundations of honor, SDO, and RWA, and tests whether different target groups and threat types selectively activate these motives. The goal is to clarify when and why honor predicts prejudice, and to specify the conditions under which its effects diverge from broader ideological dispositions.</p>
    </div>
    <div class="project-visual">
      <img src="{{ '/assets/icons/predictors-of-prejudice.png' | relative_url }}" alt="Honor, Ideology, and Prejudice">
    </div>
  </div>

</div>
