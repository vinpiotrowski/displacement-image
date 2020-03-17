---
layout: default

---


<div class="menu">
<ul>
{% for post in site.posts | reverse %}
    <li><a href=".{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
</div>
