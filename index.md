---
layout: default
title: Localo
---
<div class="page-header">
  <h1>Localo</h1>
</div>

This project's goal is to author, through community consensus, **local government data specifications** relating to the services and information provided by local government. A related goal is to make it easier for civic developers to create additional software built on these standards.

<h2 id="principles">Principles</h2>

1. This project rigorously researches and studies existing specifications and reuses suitable existing work wherever possible. It looks for existing specifications that balance breadth of adoption with quality of modeling. It **prioritizes reuse over novelty**.

1. This specification satisfies a broad range of use cases, without requiring an exhaustive vocabulary of terms. It **focuses on flexibility** to do more with fewer terms.

1. A fact that many specifications overlook is that our knowledge of the world is imprecise and uncertain. This specification attempts, as much as possible, to make it easy to represent **real world data** while preserving clarity and meaning.

<div class="well well-white">
  <ul class="nav nav-tabs no-js">
    <li class="disabled"><a>Examples of imprecision and uncertainty:</a>
    <li class="active"><a href="#example-date">Imprecise date</a></li>
    <li><a href="#example-contact">Missing contact details</a></li>
    <li><a href="#example-sponsor">Ambiguous bill sponsor</a></li>
  </ul>

  <div class="tab-content">
    <div class="tab-pane active" id="example-date">
      A civil society organization doesn't know the precise date on which a legislator assumed office. Its legislative information service should nonetheless be able to publish an approximate date in that legislator's profile.
    </div>
    <div class="tab-pane" id="example-sponsor">
      When extracting the sponsors of a bill from a legislature's website, it isn't immediately possible to disambiguate a sponsor's name and link to the appropriate legislator or committee profile. A legislative information service should be able to publish the incomplete sponsor information, without having to first determine whether that information belongs to a legislator or a committee.
    </div>
    <div class="tab-pane" id="example-contact">
      A civil society organization has the phone number of a legislator; however, it doesn't know whether it is the capitol office number, the constituency office number or a mobile number. A data specification should be able to handle data at varying levels of detail.
    </div>
  </div>
</div>

## Process

The high-level specification development process is as follows:

1. Identify use cases and requirements for a specific [activity system](http://www.thoughtworks-studios.com/blog/stop-designing-users).
2. Research existing specifications that fulfill the use cases and requirements.
3. Author a specification and related documentation that respect the [principles](#principles).
4. Iteratively improve the specification.

Specification development works by an open process and by rough consensus. [Participation](#participation) is open and free to all.

## Specification

Jump to a section below or start at the [beginning]({{ site.url }}/specs/).

1. [Scope]({{ site.url }}/specs/#scope)
1. [Conformance]({{ site.url }}/specs/#conformance)
1. [Use cases & requirements]({{ site.url }}/specs/#use-cases-and-requirements)
1. [Standard reuse]({{ site.url }}/specs/#standard-reuse)
1. [Classes and properties]({{ site.url }}/specs/#classes-and-properties)
    1. People and organizations
        1. [Waste collection]({{ site.url }}/specs/waste-collection.html)
        2. [Planning application]({{ site.url }}/specs/planning-application.html)
1. [Serialization](/specs/#serialization)
    1. [JSON schema and examples]({{ site.url }}/specs/#schema-and-examples)
    1. [Metadata serialization]({{ site.url }}/specs/#metadata-properties)
    1. [Embedded JSON documents]({{ site.url }}/specs/#embedded-json-documents)
    1. [JSON subschema]({{ site.url }}/specs/#subschema)
1. [Change history]({{ site.url }}/specs/#history)


<h2 id="participation">Participation</h2>

Participation is free and open to anyone. These documents are **Working Drafts**. Their governance roughly follows the [W3C process](http://www.w3.org/community/about/agreements/).

* Visit the [GitHub repository](https://github.com/LocalGovDigital/Localo/tree/gh-pages), discuss [open issues](https://github.com/LocalGovDigital/Localo/issues), and create pull requests


