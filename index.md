---
title: Share
---

# Share

<p class="intro">Things I've written or put together and want to share with friends and family. Newest first.</p>

{% assign items = site.pages | where: "share", true | sort: "date" | reverse %}
<ul class="items">
{% for item in items %}
  <li>
    <span class="date">{{ item.date | date: "%-d %B %Y" }}</span>
    <a class="title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
    {% if item.summary %}<p>{{ item.summary }}</p>{% endif %}
  </li>
{% endfor %}
</ul>
