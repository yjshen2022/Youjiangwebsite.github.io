---
title: "Yamazaki Lab - Publications"
layout: gridlay
excerpt: "Yamazaki Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

Under construction

## Highlights

( For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.ch/user=2c_Vf3cAAAAJ) )

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

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

