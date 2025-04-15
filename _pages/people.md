---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---
<style>
  a {
    color: #E56915;
  }
</style>

<div class="row" style="margin-bottom: 50px;">
  <div class="col-md-12 text-center">
    <h1 style="font-size: 1.5rem; font-weight: bold; margin-bottom: 30px;">Lab Statement</h1> 
  </div>
  <div class="col-md-12">
    <p style="text-align: justify; max-width: 900px; margin: 0 auto;">
      We devote to create an inclusive and supportive environment for all members of the lab to learn from each other and work as a team. 
      We encourage the exploration of diverse ideas. We value the unique contributions of each member, and ensure mutual respect and continuous growth!      
    </p>
  </div>
</div>

<h1 class="text-center" style="font-size: 1.5rem; margin-bottom: 50px;">Lab Members</h1>

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% if post.category == "Lab member" %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<!--
<h1 class="text-center" style="font-size: 2rem; margin: 50px 0;">Lab Alumni</h1>

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% if post.category == "Lab alumni" %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
-->
