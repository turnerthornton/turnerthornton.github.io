---
layout: page
title: Archive
---

<!--# All Posts

{% for post in site.posts %}
  * {{ post.date | date: "%B %-d, %Y" }}: [ {{ post.title }} ]({{ post.url }})
{% endfor %}-->

### Articles
{% for post in site.categories['article'] %}
  * {{ post.date | date: "%B %-d, %Y" }}: [ {{ post.title }} ]({{ post.url }})
{% endfor %}

### Links
{% for post in site.categories['link'] %}
  * {{ post.date | date: "%B %-d, %Y" }}: [ {{ post.title | "<span class="link-arrow"></span></a>&rarr;</span>" }} ] ({{ post.url }})
{% endfor %}