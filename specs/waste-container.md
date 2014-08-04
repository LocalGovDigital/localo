---
layout: class
title: Waste container | Localo
id: waste-container
---

<ul class="breadcrumb">
  <li><a href="/specs/">Data Specification</a></li>
  <li><a href="/specs/#classes-and-properties">Classes and properties</a></li>
  <li class="active">Waste container</li>
</ul>

A waste container is an object detailing the properties of a container for a type of waste.

<h1 id="use-cases-and-requirements">1. Use cases &amp; requirements</h1>

1. name

    >e.g wheelie bin

1. size

    >e.g 20

1. color

    >e.g black

1. waste_type

    >e.g garden waste

1. image

    >e.g http://www.localo.org/waste/images/container_1.png

<h1 id="standard-reuse">2. Standard reuse</h1>

Few specifications exist for waste collections, and many organisations don't publish their waste collection information in machine readable format.

<h1 id="classes-and-properties">3. Classes and properties</h1>

<table>
  <thead>
    <tr>
      <th width="130">Term</th>
      <th>Mapping</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>WasteContainer</strong></td>
      <td><code><a href="http://schema.org/Thing" title="http://schema.org/Thing">schema:Thing</a></code></td>
      <td>A waste container is an object detailing the properties of a container for a type of waste</td>
    </tr>
    <tr id="rdf:type">
      <td>name</td>
      <td><code><a href="http://schema.org/name" title="http://schema.org/name">schema:name</a></code></td>
      <td>The name of the type of container</td>
    </tr>
    <tr id="rdf:type">
      <td>size</td>
      <td><code><a href="http://schema.org/Integer" title="http://schema.org/Integer">schema:Integer</a></code></td>
      <td>The size of container in litres</td>
    </tr>
    <tr id="rdf:type">
      <td>color</td>
      <td><code><a href="http://schema.org/color" title="http://schema.org/color">schema:color</a></code></td>
      <td>The color of the container</td>
    </tr>
    <tr id="rdf:type">
      <td>waste_type</td>
      <td><code><a href="" title="">localo:waste_type</a></code></td>
      <td>The type of waste the container is used for</td>
    </tr>
    <tr id="rdf:type">
      <td>image</td>
      <td><code><a href="http://schema.org/image" title="http://schema.org/image">schema:image</a></code></td>
      <td>An image of the container</td>
    </tr>
  </tbody>
</table>

<h1 id="serialization">4. Serialization</h1>

**JSON differences from other RDF serializations:**

<ul class="nav nav-tabs no-js">
  <li><a href="#count-schema">JSON Schema</a></li>
  <li><a href="#count-context">JSON-LD Context</a></li>
  <li class="active"><a href="#count-json">JSON</a></li>
  <li><a href="#count-rdf">RDF</a></li>
</ul>

<div class="tab-content no-js">
  <div class="tab-pane" id="count-schema" data-url="{{ site.url }}/schemas/waste-container.json"></div>
  <div class="tab-pane" id="count-context" data-url="{{ site.url }}/contexts/waste-container.jsonld"></div>
  <div class="tab-pane active" id="count-json" data-url="{{ site.url }}/examples/waste-container.json"></div>
  <div class="tab-pane" id="count-rdf" data-url="{{ site.url }}/examples/waste-container.ttl"></div>
</div>

<h1 id="code-lists">5. Code lists</h1>


