---
layout: home
title: Home
---

## About Me
Welcome to my portfolio. 
I break things for a living - on purpose, I promise. While others build features, I'm the person gleefully clicking buttons in the wrong order and wondering what happens when you enter "💩" in the username field. Turns out, automated testing is the perfect outlet for my chaotic energy.
I believe good testing is like a good joke - it should be clear, repeatable, and not leave everyone confused about what just happened.

## Projects

<ul>
  {% for project in site.projects %}
    <li style="margin-bottom: 20px;">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>
