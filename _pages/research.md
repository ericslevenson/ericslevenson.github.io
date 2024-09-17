---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
This page is still under construction...

My research uses satellite data, field measurements, and geospatial data analysis to produce actionable science that can inform decision makers, managers, and the public. My PhD research focuses on *improving our representation of surface water dynamics to reflect water's actual storage and movement across the landscape*. This work is building towards the capacity to monitor past and current water developments (e.g., floods, scarcity, longer-term trends) and to predict hydrologic fluxes. <br/>
<img src='/images/jimLake_banner.jpg'/>
## <a href="/files/Earth-from-Space.pdf"> On seeing Earth from space</a>

**See links for details on specific projects**
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



I view research as a productive and creative approach to generating knowledge and contributing to a resilient society. In addition to the theoretical aspect of knowledge production, I really enjoy the 'in-the-weeds' technical problem solving that is involved in constructing and analyzing datasets. Much of my work is to **convert pixels to insights.** I am always building my methodological skillset, but much of my work to this point has included the following tools:
* 'Computer Vision' algorithm development for satellite data.
  * Google Earth Engine, cloud-based SpatioTemporal Asset Catalogs (STAC), and automated geospatial analysis in Python.
* Time Series processing
* Statistics and machine learning
* Data visualization and cartography
* Field surveys (Structure from Motion drone surveys, high-precision GNSS)



{% include base_path %}



<br/>
<br/>
<br/>
<br/>
<br/>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
