---
title: "News"
layout: textlay
excerpt: "Davuluri Lab at Stony Brook University."
sitemap: false
permalink: /allnews.html
---

# News

<!-- {% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %} -->


<div class="col-sm-12 clearfix">

<ul style="overflow: hidden">
  {% for article in site.data.news %}
  <li>{{<b>article.date</b>}} <i>{{ article.headline | markdownify}}</i> </li>
  {% endfor %}
</ul>