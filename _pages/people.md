---
layout: archive
title: "Lab Members"
permalink: /people/
author_profile: true
---

<div class="row" style="background-color: #f5f5f7; padding: 50px 0; margin-bottom: 50px;">
  <div class="col-md-4">
    <h1 style="font-size: 2.5rem; font-weight: bold;">Lab Statement</h1>
  </div>
  <div class="col-md-8">
    <p>
      We strive to create an inclusive and supportive environment 
      for all members of the lab to learn from each other and work 
      as a team. We believe that we benefit most from the 
      exploration of a diverse set of ideas. We acknowledge, 
      welcome, and celebrate our differences, including those 
      related to race, ethnicity, gender identity, nationality, sexual 
      orientation, religion, disability status, and socioeconomic 
      status. We work to prevent implicit biases from negatively 
      impacting our lab and the community around us.
    </p>
  </div>
</div>

<h1 class="text-center" style="margin-bottom: 50px;">Current Lab Members</h1>

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% if post.category == "current_member" %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<h1 class="text-center" style="margin: 50px 0;">Lab Alumni</h1>

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% if post.category == "alumni" %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
