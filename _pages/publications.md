---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">

## Journal Articles
<h3>Journal Articles</h3>

{% bibliography --query @article %}

## Working Papers
<h3>Working Papers</h3>

{% bibliography --query @unpublished %}


