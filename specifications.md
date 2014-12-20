---
title: Specifications
---

{% assign specifications = (site.specifications | sort:"name" ) %}


<div class="row">
  <div class="col-md-8">
      {% for spec in specifications %}
          <h3 id="#{{ spec.name }}"><a href="specifications/{{ spec.name }}/{{ spec.version }}">{{ spec.name | capitalize }}</a></h3>
          <!-- {% include _versions-links.html %} -->

      {% endfor %}
  </div>

</div>
