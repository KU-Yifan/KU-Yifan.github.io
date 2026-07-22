---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed journal articles and preprints, in reverse chronological order. Generated from BibTeX.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

### Journal articles ({% bibliography_count --query @article %})

<div class="publications">

{% bibliography --query @article %}

</div>

### Preprints ({% bibliography_count --query @misc %})

<div class="publications">

{% bibliography --query @misc %}

</div>
