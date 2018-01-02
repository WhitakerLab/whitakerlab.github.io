---
layout: page
title: About the Whitaker Lab
excerpt: "Members of the Whitaker lab and their research interests."
---

<ul class="post-list">
{% for post in site.categories.profile %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}
    {% if post.author %}
      {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.owner %}
    {% endif %}
    {% if author.avatar contains 'http' %}
      <img src="{{ author.avatar }}" class="bio-photo" alt="{{ author.name }} bio photo"/>
    {% elsif author.avatar %}
      <img src="{{ site.url }}/images/{{ author.avatar }}" class="bio-photo" alt="{{ author.name }} bio photo"/>
    {% endif %}
   <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>