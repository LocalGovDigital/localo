---
title: Waste type
subtitle: A waste type is a grouping for items to be identified as waste.
id: waste-type
type: spec
---

<h2 id="use-cases-and-requirements">1. Use cases &amp; requirements</h2>

1. name

    >e.g garden waste

1. allowed items

    >e.g leaves, grass

1. disallowed items

    >e.g food waste


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
      <td><strong>WasteType</strong></td>
      <td><code><a href="http://schema.org/Thing" title="http://schema.org/Thing">schema:Thing</a></code></td>
      <td>A waste type is a grouping for items to be identified as waste.</td>
    </tr>
    <tr id="rdf:type">
      <td>name</td>
      <td><code><a href="http://schema.org/name" title="http://schema.org/name">schema:name</a></code></td>
      <td>The name of the type of waste</td>
    </tr>
    <tr id="rdf:type">
      <td>allowed items</td>
      <td>List of @ids</td>
      <td>A list of allowed waste items</td>
    </tr>
    <tr id="rdf:type">
      <td>disallowed items</td>
      <td>List of @ids</td>
      <td>A list of disallowed waste items</td>
    </tr>
  </tbody>
</table>

<h2 id="serialization">4. Serialization</h2>

{% include _serialization.html %}

<h2 id="code-lists">5. Code lists</h2>
