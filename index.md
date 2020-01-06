---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

## This is the home page.

Hi there.
number of posts: {{ site.posts.size }}

{% for item in site.posts %}
{{item.title}}
{% endfor %}
