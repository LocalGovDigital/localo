---
title: Waste round
subtitle: A waste round describes a list of locations to be collected from and the containers that should be collected attached to a schedule.
id: waste-round
type: spec
---

<h2 id="use-cases-and-requirements">1. Use cases &amp; requirements</h2>

1. name

    >e.g garden waste

1. properties

    >e.g

1. containers

    >e.g black bin


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
      <td><strong>WasteRound</strong></td>
      <td><code><a href="http://schema.org/Thing" title="http://schema.org/Thing">schema:Thing</a></code></td>
      <td>A waste round describes a list of locations to be collected from and the containers that should be collected attached to a schedule.</td>
    </tr>
    <tr id="rdf:type">
      <td>name</td>
      <td><code><a href="http://schema.org/name" title="http://schema.org/name">schema:name</a></code></td>
      <td>The name of the round</td>
    </tr>
    <tr id="rdf:type">
      <td>properties</td>
      <td>List of Integers</td>
      <td>A list of property UPRNs</td>
    </tr>
    <tr id="rdf:type">
      <td>containers</td>
      <td>List of @IDs</td>
      <td>A list of containers</td>
    </tr>
  </tbody>
</table>

<h2 id="serialization">4. Serialization</h2>

{% include _serialization.html %}

<h2 id="code-lists">5. Code lists</h2>
