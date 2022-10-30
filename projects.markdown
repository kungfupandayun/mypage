---
layout: post
title: Projects
permalink: /mypage/projects/

---
<ul>
{% for category in site.categories %}
    <ul>
    {% for post in category.last %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
{% endfor %}
</ul>
