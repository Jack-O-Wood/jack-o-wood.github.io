---
layout: page
title: Insurance Agency Database System
description: Oracle database design and APEX web application
image: assets/images/pic05.jpg
nav-menu: false
show_tile: false
---

<div id="main" class="alt">
<section id="one">
<div class="inner">

<header class="major">
<h1>Insurance Agency Database System</h1>
</header>

<span class="image main"><img src="assets/images/insurance-er-diagram.jpg" alt="ER Diagram" /></span>

<h2>Project Overview</h2>

<p>A comprehensive database solution for tracking insurance company policies, built as part of a team project at Fordham University's Gabelli School of Business. The system manages clients, agents, auto policies, life policies, claims, invoices, and payments.</p>

<div class="row">
<div class="6u 12u$(small)">
<h3>Tools Used</h3>
<ul>
<li>Oracle Data Modeler</li>
<li>Oracle APEX</li>
<li>SQL / PL/SQL</li>
</ul>
</div>
<div class="6u$ 12u$(small)">
<h3>Skills Demonstrated</h3>
<ul>
<li>Entity-Relationship Modeling</li>
<li>Database Normalization (3NF)</li>
<li>DDL Script Development</li>
<li>Complex SQL Queries</li>
</ul>
</div>
</div>

<hr class="major" />

<h2>Database Design</h2>

<p>The database was designed following a structured approach: conceptual modeling, logical modeling, and physical implementation. Key entities include Client, Agent, Auto Policy, Life Policy, Claim, Invoice, and Payment.</p>

<h3>Normalization</h3>
<p>All tables were normalized to Third Normal Form (3NF). Notable decisions included:</p>
<ul>
<li>Separating Car and Driver information from the Client-Auto Policy relationship to eliminate partial dependencies</li>
<li>Removing calculated fields (commissions, counts) from junction tables</li>
<li>Creating a Car_2 table to resolve transitive dependency between Car Make and Car Model</li>
</ul>

<hr class="major" />

<h2>Sample Queries</h2>

<p>The project included 12 complex SQL queries demonstrating joins, calculations, subqueries, and aggregations. Examples:</p>

<ul>
<li>Multi-table joins linking clients, policies, and agents</li>
<li>Calculated fields for total invoiced vs. total paid amounts</li>
<li>Date comparisons to identify policies needing renewal within 14 days</li>
<li>Nested subqueries comparing individual policy amounts to global averages</li>
</ul>

<hr class="major" />

<h2>APEX Implementation</h2>

<p>The database was implemented in Oracle APEX with a functional web interface for data entry and reporting.</p>

<!-- Add APEX screenshots here -->
<!-- <span class="image main"><img src="assets/images/insurance-apex.jpg" alt="APEX Interface" /></span> -->

<hr class="major" />

<ul class="actions">
<li><a href="projects.html" class="button">Back to Projects</a></li>
</ul>

</div>
</section>
</div>