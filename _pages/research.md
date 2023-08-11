---
layout: archive
title: "Research Team"
permalink: /research/
author_profile: true

---
**Principal Investigator**
![](/images/mypic.jpeg)

##Education and training:
Postdoc, University of Alberta
Postdoc, Pennsylvania State University
PhD (Microbial Ecology/Environmental Microbiology), University of Toronto 
MSc (Soil Ecology), University of Manitoba 
MSc (Nematology), University of Ghent, Belgium 
BSc (Biology), Mindanao State University, Philippines  


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
