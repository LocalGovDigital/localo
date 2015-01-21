---
title: Waste
api_version: v1
type: index
layout: api
---

<div id="sidebar">

{{ site.data.waste.spec.title }}

<hr/>

{% for p in site.data.waste.spec %}

{% if p[0] contains '/' %}
<a href="{{ site.baseurl }}{{ page.url }}#{{ p[1].displayName | downcase | escape | replace:' ','-' }}">{{ p[1].displayName }}</a>
<br/>

{% endif %}
{% endfor %}

</div>


<div id="content">

<h1>{{ site.data.waste.spec.title }}</h1>
{{ site.data.waste.spec.version }}

{% include raml_endpoint.html endpoint=site.data.waste.spec rootpath='' %}

</div>

