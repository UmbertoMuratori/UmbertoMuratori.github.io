---
title: "Presentations"
layout: gridlay
sitemap: false
permalink: /presentations/
---

## Presentations

<div class="section-card" id="pubList">
<h3>Seminars</h3>

{% bibliography --query @incollection[keywords ^= invited] %}

<h3>Conferences</h3>

{% bibliography --query @incollection[keywords != invited] %}
</div>
