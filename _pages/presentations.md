---
title: "Presentations"
layout: gridlay
sitemap: false
permalink: /presentations/
---

## Presentations

<div class="section-card" id="pubList">
<h3>Invited Talks</h3>

{% bibliography --query @incollection[keywords ^= invited] %}

<h3>Regular Talks</h3>

{% bibliography --query @incollection[keywords != invited] %}
</div>
