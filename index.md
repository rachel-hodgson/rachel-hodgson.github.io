
---
layout: home
title: Home
permalink: /
---

## Welcome!

Software Engineer based in Auckland, seeking opportunities in Sydney’s business district. I specialize in designing, building, and implementing technical solutions that boost productivity and streamline workflows for businesses. My diverse industry experience gives me a strong understanding of operational needs and user-centric design.

- **Technical background:** Embedded C++ systems for healthcare devices, Python-based workflow automation applications, Web applications leveraging Python, JavaScript, and TensorFlow for medical solutions
- **Focus areas:** workflow automation, data integration, UX for internal tools, test design
- **Tools:** Python, C++, JavaScript, TypeScript, SQL, Excel, MatLab
- **Interests:** design thinking, business analytics, pattern extraction 

### Featured Projects

{% assign featured = site.projects | where: "featured", true %}
{% for project in featured %}
- [{{ project.title }}]({{ project.url }}) — {{ project.summary }}
{% endfor %}

### Latest Case Studies

{% for project in site.projects limit:3 %}
- [{{ project.title }}]({{ project.url }}) — {{ project.summary }}
{% endfor %}
