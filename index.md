---
layout: default
--- 
hello world
{% for item in site.posts %}<a href="/portfolio{{ item.url }}">{{ item.title }}</a>{% endfor %}
[I'm an inline-style link](https://www.google.com)
