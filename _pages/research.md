---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<br/><img src='/images/2023_06_jimlake_talkeetnas.jpg' width="600" height="150"/>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
