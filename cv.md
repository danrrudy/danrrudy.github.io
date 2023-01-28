---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
permalink: /cv
title: CV and Professional Work

---

<object data="/assets/CV.pdf" width="750" height="750" type='application/pdf'></object>
<div class="row">
  <div class="column"></div>
  <div class="column"></div>
</div>
## Updates on my work:
<ul>
  {% for post in site.posts %}
  	{% if post.tags contains "work" %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>.