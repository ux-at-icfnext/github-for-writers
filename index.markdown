---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome to the sandbox

### Checkout some post:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
