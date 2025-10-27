---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
list_title: Sestava 8 pohybů
---

### zahajovací fáze( pozdrav), zvedání rukou, zahnání opice, obejmutí kolene, koňská hlava, oblycne ruce, zlatý kohout, kop patou, česaní ptačího ocasu, pata, dlaň do dlaně, dlaně, zakončující fáze, postoj.



<ul>
  {% for post in site.posts %}
    {% if post.categories contains "sestava8" %}
      <li><h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3></li>
    {% endif %}
  {% endfor %}
</ul>


