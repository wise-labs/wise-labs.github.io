---
layout: page
title: Members
permalink: /members/
---

{% for staff_member in site.members %}
<h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
<p>{{ staff_member.content | morkdownify }}</p>
{% endfor %}
