---
title: Localo
---

<p class="lead">Localo is a <a href="http://localgovdigital.info/localgov-digital-makers">LocalGov Digital Makers</a> project to create by community consensus <strong>local government data and <abbr title="Application Programming Interface">API</abbr> specifications</strong> relating to the services and information provided by local government.</p>

<div class="row">
  <div class="col-md-7">
  	<h2>What is Localo?</h2>

  	<p>In local government we tend to buy line of business systems by service and for a specific task (e.g. Planning or Cleansing) and often from a big supplier. Typically they're not very open being either difficult and/or expensive to get data in or out which makes things difficult when we want to be able to integrate systems to allow end-to-end digital services which means users should be able to view current and correct information as well as transact in real-time. Councils also want to be able to evaluate performance which relies on being able to access appropriate data from their line of business systems. When access to the data within the line of business systems is possible, it's often bespoke. This means the other systems using data from the line of business systems would need to be updated if there was a change to, or replacement of, that system increasing cost and time required which potentially affects the viability of making the change.</p>

  	<p>There are two parts to the project (<a href="about.html#principles">where the work hasn't been done already</a>).</p>

  	<p>The first is to specify the <strong>data models</strong>. Data models specify how to describe a <em>thing</em>. Taking a bin as an example the table below shows what some of the standard attributes might be:</p>

  	<dl class="dl-horizontal">
		<dt>Size</dt>
		<dd>This could be the size or capacity of the container in litres.</dd>
		<dt>Type</dt>
		<dd>This could be the type of container e.g. <samp>wheeled bin</samp>, <samp>sack</samp>, <samp>box</samp>, <samp>caddy</samp>. Depending on the scenario this list of types could be fixed, there could be suggested values or it could be open to any value</dd>
		<dt>Colour</dt>
		<dd>This could be the colour of the container and like <code>Type</code>, could be open or have a list of values. Alternatively it could be something that computers understand such as a hex code <samp>#000000</samp> (the hex code for black)</dd>
	</dl>

  	<p>The second part of the project is to develop an <strong>API specification</strong>. APIs are a mechanism for other applications and hardware to interact with a system. The interactions allows access to the data within the system together with some or all of the funcationlity it provides. The APIs typically use web technologies so analogy is that they are a set of web pages that don't make much sense to humans, but do to machines! They are an integral part of how the systems in companies such as Amazon, Google, Facebook, PayPal and Twitter work.</p>

  	<h3>What are the benefits?</h3>

  	<p>Standardising the interfaces between systems should allow a more modular IT architecture. This has the potential to reduce reliance on a single supplier by allowing components to easily be replaced without having to redevelop neighbouring systems. It can also help increase competition between suppliers and support new entrants including civic coders because they don’t have to supply an all-or-nothing solution and the specification for the interface is open. Where development is required, throughput may also be increased by allowing teams to work in parallel on different parts and release their work faster.</p>

  	<p>A standard should reduce integration costs because for those suppliers that adopt the standard it will no longer be a bespoke integration. Councils will then be more easily able to share and reuse the work of others and collaborate without having to use all the same technology. That also increases the options for supporting one another and should create consistency for things like reporting.</p>

	<p>The standard also infers a base level of functionality a system must provide helping to ensure that systems that are developed or procured work the way council want them to – based on the identified user needs.</p>

	<p>Bringing this all together means we should be able to concentrate on building great user experiences, collaboratively.</p>

  	<p>The <strong>Gubbins of Government</strong> video below by <a href="https://fodengrealy.com/">Foden Grealy</a> explains in "plainish English" how making systems modular and shareable can change government for the better.</p>

	<iframe width="560" height="315" src="//www.youtube-nocookie.com/embed/02__3UTqXmU?rel=0" frameborder="0" allowfullscreen></iframe>

  </div>
  <div class="col-md-4 col-md-push-1">
	<h3>Get involved</h3>
	<ul class="list-unstyled">
		<li>Register your interest on <a href="http://pipeline.localgovdigital.info/">Pipeline</a></li>
		<li>Post on the <a href="http://localgovdigital.discoursehosting.net/">LocalGov Digital Talk</a></li>
		<li>Tweet <a href="https://twitter.com/LGMakers">@LGMakers</a></li>
		<li><a href="#events">Attend an event</a></li>
	</ul>

    	<h3 id="events">Upcoming Events</h3>
	<div class="list-group">
		<a href="http://www.localdirect.gov.uk/event/local-digital-co-design-day-2/" class="list-group-item">
			<h4 class="list-group-item-heading">Local Digital Co-Design Day 2 | London</h4>
			<p class="list-group-item-text">Friday 28 November @ 9:30 - 17:00</p>
		</a>
	</div>
  </div>
</div>
