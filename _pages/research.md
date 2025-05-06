---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research addresses basic and applied questions integrating the following topics:

* **Arctic Environmental Change** <br/>
* **Physical Hydrology** <br/>
* **Geospatial AI** 
<p align='justify'>  
Specifically, I aim to improve our representation of surface water dynamics to reflect water's actual storage and movement across the landscape in order to (a) address key questions about the changing Arctic (where surface water is prevalent and data is sparse), and (b) to improve water resource monitoring capabilities. Towards this end, of my time and expertise is dedicated to developing models, algorithms, and strategies to produce state-of-the-art surface water surveys using satellite data. </p>
 <img src='/images/jimLake_banner.jpg'/>

**See links for details on specific projects**
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br/>
<p align='justify'> 
I view research as a productive and creative approach to generating knowledge and contributing to a resilient society. In addition to the theoretical aspect of knowledge production, I really enjoy the 'in-the-weeds' technical problem solving that is involved in constructing and analyzing datasets. Much of my work is to **convert pixels to insights.** I am always building my methodological skillset, but much of my work to this point has included the following tools:</p>
 
* 'Computer Vision' algorithm and model development for satellite data.
  * Google Earth Engine, cloud-based SpatioTemporal Asset Catalogs (STAC), and automated geospatial analysis in Python.
* Time Series processing
* Statistics and machine learning
* Data visualization and cartography
* Field surveys (Structure from Motion drone surveys, high-precision GNSS)



{% include base_path %}



<br/>
<br/>
<br/>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
