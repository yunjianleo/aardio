---
title:  "代码段"
---

#### 随手记代码

<ul>
{% for object in site.data.list %}
  <li>
      <a href="{{ object.name }}">{{ object.title }}</a>
  </li>
{% endfor %}
</ul>