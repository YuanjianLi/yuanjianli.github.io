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

<li>Quick facts: I, as the first-order author, published 3 Transactions (2 IEEE TWC, 1 IEEE TCom), 1 Letter (IEEE WCL) and 2 Conferences (2 IEEE ICC) amid my PhD. I thus have gained extensive knowledge of Python (Pytorch, tensorflwo, etc.) and Matlab.  
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

