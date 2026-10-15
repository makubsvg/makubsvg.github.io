---
layout: default
title: Projects
permalink: /projects/
---

<h1>Projects</h1>
{% assign projects = site.projects | sort: "date" | reverse %}
<ul>
{% for project in projects %}
  <li>
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
    — {{ project.description }}
  </li>
{% endfor %}
</ul>