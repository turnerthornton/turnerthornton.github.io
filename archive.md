---
layout: page
title: Archive
---





### Articles
{% for post in site.categories['article'] %}
  * {{ post.date | date: "%B %-d, %Y" }}: [ {{ post.title }} ]({{ post.url }})
{% endfor %}

### Links
{% for post in site.categories['link'] %}
  * {{ post.date | date: "%B %-d, %Y" }}: [ {{ post.title }} ]({{ post.url }}) <span class="link-arrow">&rarr;</span>
{% endfor %}


### All Posts

  {% if site.posts %}
    <h1 class="post-title"><a href="{{ page.link }}">{{ page.title }} <span class="link-arrow"></span></a>&rarr;</h1>
  {% else %}
    <h1 class="post-title">{{ page.title }}</h1>
  {% endif %}