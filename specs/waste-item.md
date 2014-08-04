---
layout: class
title: Waste item | Localo
id: waste-item
---

<ul class="breadcrumb">
  <li><a href="/specs/">Data Specification</a></li>
  <li><a href="/specs/#classes-and-properties">Classes and properties</a></li>
  <li class="active">Waste item</li>
</ul>

A waste item is an object detailing the properties of a single of waste.

<h1 id="use-cases-and-requirements">1. Use cases &amp; requirements</h1>

1. name

    >e.g newspaper

1. category

    >e.g mixed paper and cardboard

1. recycle

    >e.g true

1. refuse

    >e.g false

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
      <td><strong>WasteItem</strong></td>
      <td><code><a href="http://schema.org/Thing" title="http://schema.org/Thing">schema:Thing</a></code></td>
      <td>A waste item is an object detailing the properties of a single of waste</td>
    </tr>
    <tr id="rdf:type">
      <td>name</td>
      <td><code><a href="http://schema.org/name" title="http://schema.org/name">schema:name</a></code></td>
      <td>The name of the type of waste</td>
    </tr>
    <tr id="rdf:type">
      <td>category</td>
      <td><code><a href="http://schema.org/category" title="http://schema.org/category">schema:category</a></code></td>
      <td>The category of the type of waste</td>
    </tr>
    <tr id="rdf:value">
      <td>recycle</td>
      <td><code><a href="http://schema.org/Boolean" title="http://schema.org/Boolean">schema:Boolean</a></code></td>
      <td>Whether the item can be recycled</td>
    </tr>
    <tr id="rdf:value">
      <td>refuse</td>
      <td><code><a href="http://schema.org/Boolean" title="http://schema.org/Boolean">schema:Boolean</a></code></td>
      <td>Whether the item should not be included in recycling</td>
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
  <div class="tab-pane" id="count-schema" data-url="{{ site.url }}/schemas/waste-item.json"></div>
  <div class="tab-pane" id="count-context" data-url="{{ site.url }}/contexts/waste-item.jsonld"></div>
  <div class="tab-pane active" id="count-json" data-url="{{ site.url }}/examples/waste-item.json"></div>
  <div class="tab-pane" id="count-rdf" data-url="{{ site.url }}/examples/waste-item.ttl"></div>
</div>

<h1 id="code-lists">5. Code lists</h1>


