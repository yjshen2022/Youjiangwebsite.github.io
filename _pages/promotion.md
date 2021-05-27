---
title: "Yamazaki Lab - Promotion"
layout: pagelay
excerpt: "Yamazaki Lab -- Promotion"
permalink: /promotion/
---

# Promotion

Highlight from our lab activity! If you are interested in, please consider to [join us]({{ site.url }}{{ site.baseurl }}/joinus/)!

<p> &nbsp; </p>

#### We are a very active research team with a nice diversity!
Group photo in Farewell Gathering @ Komaba Campus (March 2021)

<img src="{{ site.url }}{{ site.baseurl }}/images/picture/DLab_20210324.jpg" width="40%"/><br>

<p> &nbsp; </p>

#### Yamazaki's talk in public event (Sep 2020)

Lab PI Yamazaki made a talk in IIS UTokyo public event. The recorded talk (in Japanese) is available on <a href="https://live.nicovideo.jp/watch/lv327827607">"Nico Nico Video"</a>
東京大学生産技術研究所の公開イベント「潜入！工学研究最前線」に、山崎が登壇しました。ライブ講演の録画を<a href="https://live.nicovideo.jp/watch/lv327827607">ニコニコ生放送タイムシフト</a>で見ることができます。

<a href="https://live.nicovideo.jp/watch/lv327827607">
<img src="https://nicolive.cdn.nimg.jp/live/simg/img/202008/2000784.df1f8b.jpg" width="40%"/>
</a><br>

<p> &nbsp; </p>

#### Yamazaki's interview on Top Researchers (Jul 2019)
Top Researchersという最先端研究を紹介するWebメディアに、<a href="https://top-researchers.com/?p=2801">山崎のインタビュー</a>が掲載されました。山崎研究室の研究内容や、その面白さや応用可能性について、インタビュー形式でまとめられています。

<a href="https://top-researchers.com/?p=2801">
<img img src="{{ site.url }}{{ site.baseurl }}/images/picture/TopResearchers.jpg" width="40%"/>
</a><br>

<p> &nbsp; </p>

#### Also, we are in the exciting research institute in a great location!
The official introduction video of IIS UTokyo. Please also visit the <a href="https://www.iis.u-tokyo.ac.jp/ja/about/feature/">institute webpage</a>.
<iframe width="560" height="315" src="https://www.youtube.com/embed/4O3IarsAN1U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<p> &nbsp; </p>











<!--

Jump to: [Leiden](#leiden), [ETHZ](#ethz), [Cornell](#cornell), [St Andrews](#st-andrews)


## Leiden

#### Timelapse of our STM assembling [(see LION news item)](https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN):
<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>


#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/promo/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>


First advertisement.
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >
</figure>


## ETHZ
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>

## Cornell
From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>

## St Andrews
From the [group of Felix Baumberger](http://dqmp.unige.ch/baumberger/) (now at University of Geneva).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">
</figure>

-->
