---
layout: default
title: Home
permalink: /
---

## Welcome!

### Product Development Engineer · Open to freelance/contract work
#### I help teams and companies turn ambiguous problems or processes into tested, streamlined outcomes.

Software Engineer based in Auckland, seeking opportunities in Sydney’s business district. I specialize in designing, building, and implementing technical solutions that boost productivity and streamline workflows for businesses. My diverse industry experience gives me a strong understanding of operational needs and user-centric design.

**Technical background:** Embedded C++ systems for healthcare devices, Python-based workflow automation applications, web applications leveraging Python, JavaScript, and TensorFlow for medical solutions

**Focus areas:** 
- Systems thinking & translating business needs into technical requirements
- Prototyping to validate quickly
- Stakeholder communication & documentation
- Diverse industry knowledge to understand your purpose
- Testing design, workflow automation, data integration

**Tools:** Python, C++, JavaScript, TypeScript, SQL, Excel, MatLab

### Featured Projects

{% assign featured = site.projects | where: "featured", true %}
{% for project in featured %}
- [{{ project.title }}]({{ project.url }}) — {{ project.summary }}
{% endfor %}
