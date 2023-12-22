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
<div style="float: left; width: 200; box-sizing: border-box; padding-right: 20px;">
  <img src="../images/profile.png" alt="Alt text" style="width: auto; max-height: calc(4em * 4);">
</div>

<div style="float: left; width: 200; box-sizing: border-box;">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed faucibus augue ut ex varius, at varius justo pharetra. Integer et facilisis massa.
  <br>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed faucibus augue ut ex varius, at varius justo pharetra. Integer et facilisis massa.
  <br>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed faucibus augue ut ex varius, at varius justo pharetra. Integer et facilisis massa.
  <br>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed faucibus augue ut ex varius, at varius justo pharetra. Integer et facilisis massa.
</div>


