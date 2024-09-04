---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
![DJI_0223-3](https://github.com/user-attachments/assets/46ccc3da-786f-421a-9f7d-52af7484ae60)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
