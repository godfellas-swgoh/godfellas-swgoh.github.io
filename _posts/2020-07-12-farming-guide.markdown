---
layout: post
title: "Farming guide"
date: 2020-07-12 12:07:00 +0200
categories: swgoh
---

<table>
  {% for row in site.data.farming-guide %}
  {% if forloop.first %}
  <tr>
  {% for pair in row %}
    <th>{{ pair[0] }}</th>
  {% endfor %}
  </tr>
  {% endif %}
  <tr>
  {% for pair in row %}
    <td>{{ pair[1] }}</td>
  {% endfor %}
  </tr>
{% endfor %}
</table>

