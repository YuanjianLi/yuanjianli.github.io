---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


A comprehensive track record can be found on my [Google Scholar page](https://scholar.google.com/citations?hl=en&user=x0KLyqgAAAAJ).

The following listed papers had been published on or submitted to top-tier IEEE Transactions or flag-ship IEEE conference series amid my PhD-pursuing phase, for all of which I play the role as the first-order author. 

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
{% if year != written_year %}
<h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
{% capture written_year %}{{ year }}{% endcapture %}
{% endif %}
{% include archive-single.html %}
{% endfor %}

