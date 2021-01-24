---
title: "Yamazaki Lab - Publications"
layout: pagelay
excerpt: "Yamazaki Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Highlights

( For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.ch/user=2c_Vf3cAAAAJ) )

{% include pub_highlight.html %}

<p> &nbsp; </p>


## Full List
### == Research mainly lead by Yamazaki Lab ==

{% for publi in site.data.publist %}
{% if publi.dlab == 1 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

### == Collaboration work ==

{% for publi in site.data.publist %}
{% if publi.dlab == 0 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

### == Publications in Japanese Journal ==
#### -- Research mainly lead by Yamazaki Lab
{% for publi in site.data.publist-J %}
{% if publi.dlab == 1 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br />{{ publi.e-title }}<br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

#### -- Collaboration work
{% for publi in site.data.publist-J %}
{% if publi.dlab == 0 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br />{{ publi.e-title }}<br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

