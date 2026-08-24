---
layout: page
permalink: /presentations/
title: presentations
description: Conference presentations and invited talks, labeled international/domestic.
nav: true
nav_order: 3
---

{% assign upcoming = site.data.presentations | where: "upcoming", true %}
{% assign past = site.data.presentations | where_exp: "p", "p.upcoming != true" %}
{% assign years = past | group_by: "year" | sort: "name" | reverse %}

<div class="publications">

{%- if upcoming.size > 0 %}
  <h2 class="bibliography">Upcoming</h2>
  <ol class="bibliography">
    {%- for entry in upcoming %}{% include presentation_entry.liquid entry=entry %}{% endfor -%}
  </ol>
{%- endif %}

{%- for y in years %}
  <h2 class="bibliography">{{ y.name }}</h2>
  <ol class="bibliography">
    {%- for entry in y.items %}{% include presentation_entry.liquid entry=entry %}{% endfor -%}
  </ol>
{%- endfor %}

</div>
