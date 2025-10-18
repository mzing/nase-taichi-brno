---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
list_title: Stará pěstní sestava
---

Pěstní sestava

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "sestava1" %}
      <li><a href="/nase-taichi-brno{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


