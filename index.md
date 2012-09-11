---
layout: page
title: Data Errata
tagline: tidbits of ennui
---
{% include JB/setup %}

Scatalogical humor: [Twitter](http://twitter.com/chilcote)

Habitual listening: [Rdio](http://www.rdio.com/#/people/chilcote)

### Quick hits

Parse your `history` to show the most often used commands:
    
    history | awk '{print $2}' | awk 'BEGIN{FS="|"}{print $1}' | sort | uniq -c | sort -n | tail -n 20 | sort -nr

    
## Memory dump

Constituted astute constructs, construed and glued:

<ul class="posts">
  {% for post in site.posts limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Nosce te ipsum

When I was 13 years old, one of my chores was to mow the lawn. My father told me that the lawn mower was old and untrustworthy, and that it would be a good idea to eschew headphones so as not to miss the telltale signs of the blade flexing its centrifugal tendencies. Also, boots.

So I spent every Thursday afternoon mowing the lawn wearing sneakers and listening to OMD on my walkman, filled with absolute terror at the possibility of amputation.

This is everything you need to know about me.

