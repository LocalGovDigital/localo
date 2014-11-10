---
title: Specifications
---

{% assign cat_spec_pages = (site.pages | sort:"category" | where: "type", "spec" ) %}

<div class="row">
  <div class="col-md-4">
    <nav>
      <h3>Contents</h3>
      <ol class="list-group">
      {% for csp in cat_spec_pages %}
        {% ifchanged csp.category %}
          <li class="list-group-item"><a href="#{{ csp.category }}">{{ csp.category | capitalize }}</a></li>
        {% endifchanged %}
      {% endfor %}
      </ol>
    </nav>
  </div>

  <div class="col-md-8">
      {% for csp in cat_spec_pages %}
        {% if version_category != csp.category %}
          <h3 id="#{{ csp.category }}"><a href="{{ csp.category }}/">{{ csp.category | capitalize }}</a></h3>
          {% assign version_category = csp.category %}
          {% include _versions-links.html %}
        {% endif %}
      {% endfor %}
  </div>
</div>