---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

![DJI_0223-3](https://github.com/user-attachments/assets/3db28d76-5858-4a65-8251-1e7f4cc16bf4)


{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
