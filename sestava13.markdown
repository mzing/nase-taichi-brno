---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
list_title: Sestava 13 pohybů
---

Sestava na jednu stranu

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "sestava13" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


