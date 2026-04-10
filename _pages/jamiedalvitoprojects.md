---
layout: default
title: Projects
permalink: /projects/
---

# Projects

{% assign visible_projects = site.projects | where_exp: "project", "project.hidden_from_projects != true" %}

<div style="max-width: 1100px; margin: 0 auto;">
  {% for project in visible_projects %}
    <div style="margin-bottom: 3rem;">
      <a href="{{ project.url | relative_url }}" style="text-decoration: none; color: inherit; display: block;">
        {% if project.image %}
          <img
            src="{{ project.image | relative_url }}"
            alt="{{ project.title }}"
            style="width: 100%; max-width: 760px; height: 320px; object-fit: cover; display: block; margin: 0 auto 1.25rem auto; border-radius: 8px;"
          />
        {% endif %}

        <h2 style="margin-bottom: 0.5rem;">{{ project.title }}</h2>

        {% if project.description and project.description != "" %}
          <p style="max-width: 900px; line-height: 1.6;">{{ project.description }}</p>
        {% endif %}
      </a>
    </div>
  {% endfor %}
</div>