---
layout: default
title: "About*"
---

# Emperor of the Moon: Dramaturgy



<div class="toc">
  <h2>Contents</h2>
  <ul class="texts">
  {% for item in site.articles %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        <i>{{ item.title }}</i>, by {{ item.author}} ({{ item.first-pub}})
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
