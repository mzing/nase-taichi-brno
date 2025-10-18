---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
list_title: Sestava 8 pohybů
---

Sestava na obě strany

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "sestava8" %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


