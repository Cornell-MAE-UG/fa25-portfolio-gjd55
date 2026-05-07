---
layout: default
title: Projects
permalink: /projects/
---

# Projects

<div class="project-list">

{% for project in site.projects %}
  {% unless project.hidden_from_projects %}
    <a class="project-card" href="{{ project.url | relative_url }}">
      {% if project.image %}
        <img
          src="{{ project.image | relative_url }}"
          alt="{{ project.title }}"
          class="project-card-image"
        />
      {% endif %}

      <div class="project-card-body">
        <h2>{{ project.title }}</h2>

        {% if project.description %}
          <p>{{ project.description }}</p>
        {% endif %}
      </div>
    </a>
  {% endunless %}
{% endfor %}

</div>