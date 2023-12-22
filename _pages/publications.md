---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

![111](../images/profile.png)
<p align="left">
  <img src="../images/profile.png" alt="Your Image" height="100%">
</p>

<p align="left">
  Your text here.
</p>
<p align="left">
  Your text here.
</p>
<p align="left">
  Your text here.
</p>
<p align="left">
  Your text here.
</p>





