---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---
<br><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
<br><br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<hr-bold>
<h2>Post-doctoral researchers</h2>
<hr><br>

<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'post-doc' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>


<hr-bold>
<h2>PhD students</h2>
<hr><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>


<hr-bold>
<h2>Master students</h2>
<hr><br>
<div class="grid__wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'master' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<br><br><br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<hr-bold>
<h2>Alumni</h2>
<hr><br>
<b>Dr. Herlinde Dekeersmaecker</b><br>
Herlinde finished her PhD on <i>'Superresolution fluorescence microscopy based techniques for the study of signal transduction'</i> in February 2017 (co-promotor). <br><br>
<b>Elfriede Heerwegh</b><br>
Elfriede finished her master thesis on <i>'The role of cancer associated fibroblasts in tumor invasion'</i> in June 2019 (promotor). <br><br>
