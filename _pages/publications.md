---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ul>
<li>Please note that I am the first-order author for all publications illustrated in this page. A more comprehensive track record covering all my authored papers can be found on my <a href="https://scholar.google.com/citations?hl=en&user=x0KLyqgAAAAJ">Google Scholar page.</a>
<!--[Google Scholar page](https://scholar.google.com/citations?hl=en&user=x0KLyqgAAAAJ).-->
</li>

<li>The following listed papers within time horizon 2020-2022 had been published on or submitted to top-tier IEEE Transactions or flag-ship IEEE conference series amid my PhD-pursuing phase. Besides, those published during 2017-2018 come from research project of my MEng degree.
</li> 
</ul>
<hr>
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

