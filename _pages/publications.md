---
title: "Yang Hu - Publications"
layout: pagelay
excerpt: "Yang Hu -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

For a full publication list, see [below](#full-list) or go to [Google Scholar]("https://scholar.google.com/citations?user=UEhDbhMAAAAJ&hl=en").

## Highlights

{% include pub_highlight.html %}

<p> &nbsp; </p>


## Full List
### Original Papers (first author, reviewed)

{% for publi in site.data.publist %}
{% if publi.rlab == 1 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

<p> &nbsp; </p>

### Original Papers (collaboration, reviewed)

{% for publi in site.data.publist %}
{% if publi.rlab == 0 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

<p> &nbsp; </p>

### Conference Proceeding (reviewed)

{% for publi in site.data.publist %}
{% if publi.rlab == 2 %}
<b> {{ publi.ID }} {{ publi.title }} </b><br>
<em> {{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endif %}
{% endfor %}

<p> &nbsp; </p>
