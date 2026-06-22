---
layout: page
title: Research
permalink: research/
---

<div class="research-listing">

{% comment %} Primary research entries appear directly under the page title. {% endcomment %}
{% for project in site.data.research %}
	{% if project.status != "In Progress" and project.category != "policy" %}
		{% include cv/research-project.html project=project %}
	{% endif %}
{% endfor %}

<details class="research-section">
	<summary class="research-subtitle">Works in Progress</summary>

	{% for project in site.data.research %}
		{% if project.status == "In Progress" %}
			{% include cv/research-project.html project=project %}
		{% endif %}
	{% endfor %}

</details>

<details class="research-section">
	<summary class="research-subtitle">Policy Writing</summary>

	{% for project in site.data.research %}
		{% if project.category == "policy" %}
			{% include cv/research-project.html project=project %}
		{% endif %}
	{% endfor %}

</details>

</div>
