---
layout: sidebar-page
title: Classes Reference
permalink: /reference/class/
script: /js/search.js
---

Work in progress

## List of classes
<table>
  <tbody>
  {% assign classes = site.classes | sort: 'title' %}
  {% for class in classes %}
    <tr>
      <td><a href="{{class.url}}">{{class.title}}</a></td>
      <td>{{class.summary}}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>
