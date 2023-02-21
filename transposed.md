---
layout: default
title: transposed
published: false
---


{% for row in site.data.transposed %}
<p><img src="{{site.baseurl}}/assets/gif/{{row.text | append: ".gif"}}" style="float:left;margin-right:5px;"/>{{row.tnc}}</p>
{% endfor %} 
