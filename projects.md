---
layout: page
title: "Research Projects"
permalink: /projects/
---

## Research Projects

Here are some of the research projects I've worked on:

<ul>
  {% for project in site.data.research_projects %}
    <li>
      <strong>{{ project.title }}</strong> ({{ project.year }})<br>
      {{ project.description }}<br>
      <a href="{{ project.link }}">View Project</a>
    </li>
  {% endfor %}
</ul>

