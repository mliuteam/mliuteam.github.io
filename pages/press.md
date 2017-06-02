---
layout: page
show_meta: false
title: "Pressed articles"
subheadline: "Our research highlights"
header:
   image_fullwidth: "logowide.png"
permalink: "/press/"
---
<ul>
    {% for post in site.categories.press %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>