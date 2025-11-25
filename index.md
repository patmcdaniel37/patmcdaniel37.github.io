---
layout: home
title: Home
---

## About Me
Welcome to my portfolio. I am passionate about building robust automated testing solutions. Below are some of the key projects I am working on.

## Projects

<ul>
  {% for project in site.projects %}
    <li style="margin-bottom: 20px;">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>
