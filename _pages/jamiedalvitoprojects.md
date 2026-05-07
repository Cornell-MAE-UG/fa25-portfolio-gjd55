---
layout: default
title: Projects
permalink: /projects/
---

# Projects

**Project count:** {{ site.projects | size }}

**Visible project count:** {{ site.projects | where_exp: "project", "project.hidden_from_projects != true" | size }}

## Debug list of all loaded projects

{% for project in site.projects %}
- **title:** {{ project.title }}
  - **path:** {{ project.path }}
  - **url:** {{ project.url }}
  - **hidden_from_projects:** {{ project.hidden_from_projects }}
{% endfor %}

## Direct ODP link

[Go to ODP]({{ "/projects/odp/" | relative_url }})