---
title: "Service"
layout: gridlay
sitemap: false
permalink: /service/
---


{% if site.data.teaching %}
# Teaching

{% for award in site.data.teaching %}
* {{ teaching.name }}
{% endfor %}
{% endif %}

{% if site.data.community_service %}
# Community Service

{% for award in site.data.community_service %}
* {{ community_service.name }}
{% endfor %}
{% endif %}

{% if site.data.leadership_service %}
# Leadership Service

{% for award in site.data.leadership_service %}
* {{ leadership_service.name }}
{% endfor %}
{% endif %}

{% if site.data.academic_service %}
# Academic Service

{% for award in site.data.academic_service %}
* {{ academic_service.name }}
{% endfor %}
{% endif %}

