---
title: Waste container
subtitle: A waste container is an object detailing the properties of a container for a type of waste.
id: waste-container
type: spec
---

<h2 id="use-cases-and-requirements">1. Use cases &amp; requirements</h2>

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

<h2 id="serialization">4. Serialization</h2>

{% include _serialization.html %}

<h2 id="code-lists">5. Code lists</h2>