---
title: Sitemap
layout: page
---

<!-- Sitemap -->
## Pages
{% for page in site.pages %}
  {% if page.title and page.title != "" and page.title != "Thank You" %}
  <li>
    <a href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
  </li>
  {% endif %}
{% endfor %}

## Blog Posts
{% for post in site.posts %}
<li>
  <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
</li>
{% endfor %}
