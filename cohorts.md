---
layout: page
title: Cohorts
description: A listing of course cohorts
---
<h1>Course Cohorts</h1>

<ul>
  {% for cohort in site.cohorts %}
    <li>
      <h2><a href="{{site.baseurl}}{{ cohort.url }}">{{ cohort.title }}</a></h2>
    </li>
  {% endfor %}
</ul>