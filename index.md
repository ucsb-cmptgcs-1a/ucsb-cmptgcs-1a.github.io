---
title: UCSB CMPTGCS 1A
---

# Computer Programming and Organization I

<div id="about" data-role="collapsible" data-collapsed="true" markdown="1">
<h2>About this course</h2>

A course taught in the [College of Creative Studies](http://www.ccs.ucsb.edu) at
[UC Santa Barbara](http://www.ucsb.edu).

This site is maintained in this github repo: <https://github.com/ucsb-cmptgcs-1a/ucsb-cmptgcs-1a.github.io>.

* [Older materials from Conrad's cs1a wiki](https://foo.cs.ucsb.edu/cs1a) site.
* [Older materials from Conrad's personal website](https://www.cs.ucsb.edu/~pconrad/ccs)

Past offerings of CMPTGCS 1A

* [Fall 2016, Phill Conrad](https://ucsb-cmptgcs-1a-f16.github.io)

</div><!-- about -->


<div id="textbooks" data-role="collapsible" data-collapsed="false">
  <h2>Textbooks</h2>
    <ul>
      {% assign textbooks = site.textbooks | sort: 'custom_sort_order' %}
      {% for textbook in textbooks %}
         <li {% if topic.indent %} class="indent" {% endif %}><a href="{{textbook.url}}">{{ textbook.title }}</a>&mdash;{{textbook.desc}}</li>
      {% endfor %}
    </ul>
</div>


<div id="topics" data-role="collapsible" data-collapsed="false">
  <h2>Topics</h2>
  <ul>
   {% for topic in site.topics %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>



<div id="resources" data-role="collapsible" data-collapsed="false">
  <h2>Resources</h2>
  <ul>
   {% for topic in site.resources %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>

<div id="tutorials" data-role="collapsible" data-collapsed="false">
  <h2>Tutorials</h2>
  <ul>
   {% for t in site.tutorials %}
     <li {% if t.indent %} class="indent" {% endif %} ><a href="{{t.url}}">{{ t.topic }}</a>&mdash;{{t.desc}}</li>
   {% endfor %}
  </ul>
</div>

