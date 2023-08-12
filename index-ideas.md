---
title: Ideas
layout: toc
style: toc
permalink: /ideas/
---
<!--
*	[The UX Designer&apos;s Responsibility](design-philosophy.html) We're creating the public marketplaces, social clubs, and business settings for the 21st century.
-->
<h1>{{ page.title }}</h1>
<ul>
{% for article in site.ideas %}
  <li><a href="{{ site.baseurl }}{{ article.url }}">{{ article.title }}</a>  {{ article.description }}</li>
{% endfor %}
</ul>