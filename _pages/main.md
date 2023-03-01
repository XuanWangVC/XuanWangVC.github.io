---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /main/
  - /main.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
{% include_relative includes/intro.md %}

If you like the template of this homepage, welcome to star and fork my open-sourced template version [AcadHomepage ![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io?style=social)](https://github.com/RayeRen/acad-homepage.github.io).

{% include_relative includes/news.md %}

# 📝 Selected Publications 
**Equal contribution**$^\star$
**Corresponding author**$^\dagger$

{% include_relative includes/pubs/early.md %}