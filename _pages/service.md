---
title: "Service"
layout: gridlay
sitemap: false
permalink: /service/
---


{% if site.data.teaching %}
# Teaching

{% for publi in site.data.teaching %}
* {{ publi.name }}
{% endfor %}
{% endif %}

{% if site.data.community_service %}
# Community Service

{% for publi in site.data.community_service %}
* {{ publi.name }}
{% endfor %}
{% endif %}

{% if site.data.leadership_service %}
# Leadership Service

{% for publi in site.data.leadership_service %}
* {{ publi.name }}
{% endfor %}
{% endif %}

{% if site.data.academic_service %}
# Academic Service

{% for publi in site.data.academic_service %}
* {{ publi.name }}
{% endfor %}
{% endif %}

