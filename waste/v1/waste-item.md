---
title: Waste item
subtitle: A waste item is an object detailing the properties of a single of waste.
id: waste-item
type: spec
---

<h2 id="use-cases-and-requirements">1. Use cases &amp; requirements</h2>

1. name

    >e.g newspaper

1. category

    >e.g mixed paper and cardboard

1. recycle

    >e.g true

1. refuse

    >e.g false

<h2 id="standard-reuse">2. Standard reuse</h2>

Few specifications exist for waste collections, and many organisations don't publish their waste collection information in machine readable format.

<h2 id="classes-and-properties">3. Classes and properties</h2>

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

<h2 id="serialization">4. Serialization</h2>

{% include _serialization.html %}

<h2 id="code-lists">5. Code lists</h2>