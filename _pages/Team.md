---
title: "Team"
permalink: /team/
layout: single
author_profile: true
classes: wide
---

{% include base_path %}

## Principal Investigator
<div class="team-grid">
  {% for m in site.data.team.pi %}
    {% include team-card.html member=m %}
  {% endfor %}
</div>

## Staff
<div class="team-grid">
  {% for m in site.data.team.staff %}
    {% include team-card.html member=m %}
  {% endfor %}
</div>

## Students
<div class="team-grid">
  {% for m in site.data.team.students %}
    {% include team-card.html member=m %}
  {% endfor %}
</div>
