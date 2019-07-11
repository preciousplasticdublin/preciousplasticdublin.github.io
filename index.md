---
layout: page
permalink: /
---


Precious Plastic Dublin is a volunteer collective working on practical solutions to plastic waste and pollution in Dublin. As part of the 'Precious Plastic’ global movement, we aim to bring plastic recycling closer to the local community, enabling the public to transform their own waste, while demonstrating the remaining value of plastic waste. 


# News

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %} 
  
  {% else if %}
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

