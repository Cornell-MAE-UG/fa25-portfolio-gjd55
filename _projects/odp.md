---
layout: default
title: Projects
permalink: /projects/
---

# Projects

<p>Total projects loaded: {{ site.projects | size }}</p>

<p><a href="{{ "/projects/odp/" | relative_url }}">Direct link to ODP page</a></p>

<ul>
{% for project in site.projects %}
  <li>
    <strong>{{ project.title }}</strong><br>
    file: {{ project.path }}<br>
    url: {{ project.url }}<br>
    hidden_from_projects: {{ project.hidden_from_projects }}
  </li>
{% endfor %}
</ul>