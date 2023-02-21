---
title: Technical Notes
nav_order: 10
layout: page
---

<h1>Technical Notes</h1>

Technical notes are included for  most sounds on the relevant pages. They are collected together here for reference. 

<details  markdown="block">
  <summary>
    Page contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>


{% for row in site.data.tech %}
## {{ row.description }}

{% include {{row.tech | prepend: "tech/"}} %}

{% endfor %}

[Back to top](#top)