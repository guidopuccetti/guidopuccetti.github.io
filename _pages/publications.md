---
title: "Guido Puccetti ~ Publications"
layout: gridlay
excerpt: "Guido Puccetti ~~ Publications."
sitemap: false
permalink: /publications/
---


# Publications

See below for an annotated list, or visit [Google Scholar](https://scholar.google.ch/citations?hl=it&user=9gMz-LgAAAAJ)
<p> &nbsp; </p>
{% for publi in site.data.publist %}

  <img src="{{ site.url }}{{ site.baseurl }}/images/publications/{{ publi.image }}" class="img-responsive" height="110px" width="85px" style="float: left" /><br />
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a><br />
  <a class="text-danger"><strong> {{ publi.news1 }}</strong></a>

{% endfor %}
