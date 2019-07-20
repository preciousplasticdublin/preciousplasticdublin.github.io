---
layout: page
permalink: /
---


Precious Plastic Dublin is a volunteer collective working on practical solutions to plastic waste and pollution in Dublin. As part of the [Precious Plastic](https://preciousplastic.com) global movement, we aim to bring plastic recycling closer to the local community, enabling the public to transform their own waste, while demonstrating the remaining value of plastic waste. 

# Sign up for our newsletter

Sign up for our [newsletter by clicking here](https://mailchi.mp/99718c0ae694/precious-plastic-dublin) and you receive our Top 5 tips on how to have a healthier relationship with plastic. 

# News

<div class="tiles">
{% for post in site.posts %}
  {% if post.category == "team" %} 
  
  {% else if %}
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>



