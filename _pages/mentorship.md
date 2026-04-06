---
layout: default
title: "Mentorship"
permalink: /mentorship/
---

## Mentorship
I am actively involved in mentoring students and young researchers in the areas of **Biomathematics, Epidemiological Modelling, and Data Analysis**. My mentorship focuses on developing strong analytical, research, and problem-solving skills applicable to real-world challenges in public health and applied mathematics.

Through my academic and professional experience at Jordan University College and other institutions, I have supervised and guided students at different levels, including undergraduate and postgraduate studies.

### Areas of Mentorship

- Mathematical modelling of infectious diseases  
- Biostatistics and data analysis  
- Public health research  
- Academic writing and research methodology
-  

---

## Mentorship Activities

<ul>
  {% for item in site.mentorship %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>  
      ({{ item.type }} – {{ item.status }})
    </li>
  {% endfor %}
</ul>
