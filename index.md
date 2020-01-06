---
layout: home
---

## This is the home page 2.

Hi there.

number of posts: {{ site.posts.size }}

{% for item in site.posts %}
{{item.title}}
{% endfor %}
