---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Research Interests

Generative models, causal inference, time-series modeling, and decision-making under uncertainty, with applications to public health and AI for science.

## Education

- **University of Michigan** — Ph.D. candidate, expected May 2028. Advisor: Alexander Rodríguez.
- **Georgia Institute of Technology** — M.S. in Computational Science and Engineering, 2024. Advisor: Chao Zhang.
- **Georgia Institute of Technology** — M.S. in Operations Research, 2022.
- **Sun Yat-sen University** — B.S. in Theoretical and Applied Mechanics, 2021.

## Publications

*\* Equal contribution (co-first authors).*

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Teaching Experience

- **University of Michigan** — Graduate Student Instructor, CSE 598: Machine Learning for Engineering, Fall 2026.
- **Georgia Institute of Technology** — Teaching Assistant, ISyE 6644: Simulation (Online), January 2023–May 2024.
- **Georgia Institute of Technology** — Teaching Assistant, ISyE 6663: Nonlinear Optimization, Fall 2022.
