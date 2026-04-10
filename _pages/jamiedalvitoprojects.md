---
layout: default
title: Projects
permalink: /projects/
---

# Projects

{% assign visible_projects = site.projects | where_exp: "project", "project.hidden_from_projects != true" %}

<div class="projects-grid">
  {% for project in visible_projects %}
    <a href="{{ project.url | relative_url }}" class="project-card" style="text-decoration: none; color: inherit;">
      <div style="margin-bottom: 1rem;">
        {% if project.image %}
          <img
            src="{{ project.image | relative_url }}"
            alt="{{ project.title }}"
            style="width: 100%; max-width: 500px; height: 260px; object-fit: cover; display: block; margin: 0 auto; border-radius: 8px;"
          />
        {% endif %}
      </div>

      <h2>{{ project.title }}</h2>

      {% if project.description and project.description != "" %}
        <p>{{ project.description }}</p>
      {% endif %}
    </a>
  {% endfor %}
</div>