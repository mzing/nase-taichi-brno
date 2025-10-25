---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
list_title: Sestava 13 pohybů
---

# Sestava 13 forem

### Zahájení, mraky, bič, jehla, blok, zrcátko, stažení rukávu, petard úder, navíjení rukou, petarda, česání ocasu, dlaň do dlaně, dlaně, roztahování křídel jeřába, zakončení



<ul>
  {% for post in site.posts %}
    {% if post.categories contains "sestava13" %}
      <li><h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3></li>
    {% endif %}
  {% endfor %}
</ul>


