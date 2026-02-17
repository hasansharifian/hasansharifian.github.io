---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
display_categories: []
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">
  <div class="row row-cols-1">
    {% assign sorted_projects = site.projects | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
  </div>
</div>
