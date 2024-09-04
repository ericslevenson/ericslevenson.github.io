---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

![DJI_0223-3](https://github.com/user-attachments/assets/d40b75ac-ad88-48c5-9205-1852848381eb)



{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
