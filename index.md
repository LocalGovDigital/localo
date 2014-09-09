---
title: Localo
---
This project's goal is to author, through community consensus, **local government data specifications** relating to the services and information provided by local government. A related goal is to make it easier for civic developers to create additional software built on these standards.

## Principles

1. This project rigorously researches and studies existing specifications and reuses suitable existing work wherever possible. It looks for existing specifications that balance breadth of adoption with quality of modeling. It **prioritizes reuse over novelty**.

1. This specification satisfies a broad range of use cases, without requiring an exhaustive vocabulary of terms. It **focuses on flexibility** to do more with fewer terms.

1. A fact that many specifications overlook is that our knowledge of the world is imprecise and uncertain. This specification attempts, as much as possible, to make it easy to represent **real world data** while preserving clarity and meaning.


## Specifications

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


## Process

The high-level specification development process is as follows:

1. Identify use cases and requirements for a specific service.
2. Research existing specifications that fulfill the use cases and requirements.
3. Author a specification and related documentation that respect the principles.
4. Iteratively improve the specification.

Specification development works by an open process and by rough consensus. Participation is open and free to all.



## References

* The [Popolo Specification](http://popoloproject.com/).
