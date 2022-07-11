---
layout: page
title: Non Profits
---

<ul>
  {% for non_profit in collections.non_profits.resources %}
    <li>
      <a href="{{ non_profit.relative_url }}">{{ non_profit.data.title }}</a>
    </li>
  {% endfor %}
</ul>