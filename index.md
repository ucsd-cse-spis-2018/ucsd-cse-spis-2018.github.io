---
layout: default
title: "UCSD CSE SPIS: Foundations of Computer Science"
---

# {{site.course}}, {{site.year}}

<div id="info" data-role="collapsible" data-collapsed="false">
<h2>Course Information</h2>
<ul>
{% for item in site.info %}
<li><a href="{{item.url}}"  data-ajax="false">{{item.title }}</a></li>
{% endfor %}
</ul>
</div>

<div data-role="collapsible" data-collapsed="true" markdown="0">
<h2 id="labs">Lectures</h2>
  {% include lectures_for_week.html week="1"
    collapsible="true" collapsed="true" %}
  {% include lectures_for_week.html week="2"
    collapsible="true" collapsed="true" %}
  {% include lectures_for_week.html week="3"
    collapsible="true" collapsed="true" %}
  {% include lectures_for_week.html week="4"
    collapsible="true" collapsed="true" %}
  {% include lectures_for_week.html week="5" 
    collapsible="true" collapsed="true" extra_item="0902" %}
</div>

<div data-role="collapsible" data-collapsed="true" >
<h2 id="homework">Homework</h2>
{% include hwk_table.html %}
</div>

<div data-role="collapsible" data-collapsed="true" >
<h2 id="labs">Labs</h2>
{% include lab_table.html %}
</div>

<div data-role="collapsible" data-collapsed="true" >
<h2 id="labs">Topics</h2>
 <ul>
 {% for item in site.topics %}
   <li><a href="{{item.url}}">{{item.topic}}&mdash;{{item.desc}}</a></li>
 {% endfor %}
 </ul>
</div>


<div data-role="collapsible" data-collapsed="true" >
<h2 id="projects">Projects</h2>
  
  <a href="https://docs.google.com/document/d/1G3xkaaQ5wiTvDV7IlZuC_MvlSL5kofi-0xDPwThecL0"> Presentation Guidelines </a>

 <div data-role="collapsible" data-collapsed="true" id="bigdata">
 <h3>Machine Learning</h3>
 <ul>
 {% for item in site.bigdata %}
   <li><a href="{{item.url}}">{{item.topic}}&mdash;{{item.desc}}</a></li>
 {% endfor %}
 </ul>
 </div>

 <div data-role="collapsible" data-collapsed="true" id="robotics">
 <h3>Robotics</h3>
 <ul>
 {% for item in site.robotics %}
   <li><a href="{{item.url}}">{{item.topic}}&mdash;{{item.desc}}</a></li>
 {% endfor %}
 </ul>
 </div>
 
 <div data-role="collapsible" data-collapsed="true" id="webapps"> 
 <h3>Web Apps</h3>
 <ul>
 {% for item in site.webapps %}
   <li {% if item.indent %} class="indent" {% endif %} ><a href="{{item.url}}">{{item.topic}}&mdash;{{item.desc}}</a></li>
 {% endfor %}
 </ul>
 </div>
 
</div>



----

![SPIS_logo](images/SPIS_logo.jpg)
