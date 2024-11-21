---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

## Blog Posts

{% for post in site.posts %}- [{{ post.title }}]({{ post.url }})
{% endfor %}

### Old content

Some links may be broken:

{% for post in site.data.external_posts %}- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Projects

{% for project in site.data.projects %}- [{{ project.title }}]({{ project.url }})
{% endfor %}
