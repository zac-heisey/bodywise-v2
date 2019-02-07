---
title: Our Team
layout: page
subtitle: Meet the Bodywise Team
sidebar: false
menu:
  about:
    weight: 1

---

<div id="team-members">
  {% for person in site.team-members %}
  <div class="member-info">
    <img class="member-img" src="{{ person.image }}" title="{{ person.name }} | Bodywise Physical Therapy" alt="image of {{ person.name }}">
    <h3 class="member-name">{{ person.name }}</h3>
    <h4 class="member-role">{{ person.role }}</h4>
    <p class="member-bio">{{ person.content }}</p>
  </div>
  {% endfor %}
</div>
