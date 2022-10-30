---
layout: post
title: Projects
permalink: /projects/

---
<ul>
{% for category in site.categories %}
    <ul>
    {% for post in category.last %}
      <li><a href="/mypage/{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
{% endfor %}
</ul>
