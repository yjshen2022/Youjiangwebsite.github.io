---
title: "Yamazaki Lab - Award".  
layout: pagelay
excerpt: "Yamazaki Lab -- Award"
sitemap: false
permalink: /award/
---


# List of Awards for Yamazaki lab members

{% for publi in site.data.award %}
{{ publi.YearMon }} <br>
{{ publi.Awardee }} <br>
<b> {{ publi.AwardName }} </b> [ {{ publi.Organization }} ] <br>
<b> {{ publi.Achievement }}</b><br>
<em><font color="red">{{ publi.URL }}</font></em> <br>
{% endfor %}

