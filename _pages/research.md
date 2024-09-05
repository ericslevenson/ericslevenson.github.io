---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<br/><img src='/images/2023_06_jimlake_talkeetnas.jpg' width="600" height="175"/>


I enjoy the creative aspect of knowledge production, as well as the 'in-the-weeds' technical problem solving that is involved with constructing novel datasets. I am always building my methodological skillset, but much of my work to this point has included the following tools:
* 'Computer Vision' algorithm development for satellite data.
  * Google Earth Engine, cloud-based SpatioTemporal Asset Catalogs (STAC), and automated geospatial analysis in Python.
* Time Series processing
* Statistics and machine learning
* Data visualization and cartography
* Field surveys (Structure from Motion drone surveys, high-precision GNSS)

{% include base_path %}

**See below for details on specific projects**
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br/>
<br/>
<br/>
<br/>
<br/>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
