---
layout: default
title: Home
active: home
---
<section>
    {% for page in site.bookpages %}
    <a href="{{ page.url }}">{{ page.name }}</a>
    {% endfor %}
</section>