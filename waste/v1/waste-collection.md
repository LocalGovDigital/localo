---
title: Waste collection
subtitle: A waste collection is an object detailing the properties of a refuse and recycling collection.
id: waste-collection
type: spec
---
<h2 id="use-cases-and-requirements">1. Use cases &amp; requirements</h2>

1. type

    >e.g refuse, recycling, garden, food

1. date

    >e.g 201401280630Z

1. frequency

    >e.g daily, weekly, fornightly, monthly

1. exception

    >true or false

1. allowed

    >e.g cans, plastic bottles, newspaper

1. disallowed

    >e.g car batteries, paint

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
      <td>Count</td>
      <td>No <code>rdf:type</code></td>
      <td>The number of votes for an option in a vote event</td>
    </tr>
    <tr id="rdf:type">
      <td>option</td>
      <td><code><a href="http://www.w3.org/TR/rdf-schema/#ch_type" title="http://www.w3.org/1999/02/22-rdf-syntax-ns#type">rdf:type</a></code></td>
      <td>An option in a vote event</td>
    </tr>
    <tr id="rdf:value">
      <td>value</td>
      <td><code><a href="http://www.w3.org/TR/rdf-schema/#ch_value" title="http://www.w3.org/1999/02/22-rdf-syntax-ns#value">rdf:value</a></code></td>
      <td>The number of votes for an option</td>
    </tr>
  </tbody>
</table>

<h2 id="serialization">4. Serialization</h2>

{% include _serialization.html %}

<h2 id="code-lists">5. Code lists</h2>

### Option

Implementations <em class="rfc2119">may</em> use values from outside this list to reflect the diversity of waste collection options.

#### Type

* `refuse`
* `recycling`
* `garden`
* `food`

#### Frequency

* `daily`
* `weekly`
* `fortnightly`
* `monthly`