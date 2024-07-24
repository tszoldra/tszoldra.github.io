---
layout: page
permalink: /repositories/
title: repositories
description:
nav: true
nav_order: 3
---

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
---

## Data Repositories

<a href="https://chaos.if.uj.edu.pl/ZOA/index.php?which=opendata&dataset=/2402.01362">2402.01362</a>
 Catching thermal avalanches in disordered XXZ model

<a href="https://chaos.if.uj.edu.pl/ZOA/index.php?which=opendata&dataset=/2303.13940">2303.13940</a>
 Femtosecond pulse parameter estimation from photoelectron momenta using machine learning
 
<a href="https://chaos.if.uj.edu.pl/ZOA/index.php?which=opendata&dataset=/2303.13940">2211.11480</a> Tracking locality in time evolution of disordered systems

<a href="https://chaos.if.uj.edu.pl/ZOA/index.php?which=opendata&dataset=/2201.07151">2201.07151</a> Unsupervised detection of decoupled subspaces: many-body scars and beyond
