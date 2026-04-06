---
layout: archive
title: "Mentorship"
permalink: /mentorship/
author_profile: true
---

<p>
I am actively involved in mentoring students in biomathematics, epidemiology, and data analysis. 
My mentorship focuses on developing strong research, analytical, and problem-solving skills.
</p>

<h2>Mentorship Activities</h2>
<hr />

{% for post in site.mentorship reversed %}
  {% include archive-single.html %}
{% endfor %}
