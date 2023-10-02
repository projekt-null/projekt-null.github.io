---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home-banner.jpg

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
