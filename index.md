---
layout: default
title: Home
permalink: /
---

## Welcome!

### Product Development Engineer · Software and Embedded Systems · Open to freelance/contract work and remote development
#### Helping teams and companies turn ambiguous problems or processes into tested, streamlined outcomes.

Software Engineer based in Sydney, Australia. I specialize in designing, building, and implementing technical solutions that boost productivity and streamline workflows for businesses. My diverse industry experience gives me a strong understanding of operational needs and user-centric design.

**Technical background:** Embedded C++ systems for medical devices, Python-based workflow automation applications, web applications leveraging Python, Java, Typescript, JavaScript, React and Angular, as well as Android and TensorFlow development for medical solutions

**Focus areas:** 
- Systems thinking & translating business needs into technical requirements
- Prototyping to validate quickly
- Stakeholder communication & documentation
- Diverse industry knowledge to understand your purpose
- Testing design, workflow automation, data integration
- Highly regulated industries (healthcare, essential communications and networks)

**Tools:** Python, Java, C++, JavaScript, TypeScript, SQL, Excel, MatLab, Android Kotlin, React, Angular

### Featured Projects

{% assign featured = site.projects | where: "featured", true %}
{% for project in featured %}
- [{{ project.title }}]({{ project.url }}) — {{ project.summary }}
{% endfor %}
