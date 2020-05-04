---
title: About
permalink: "/about/"
layout: page
---

<div class="wrapper-inside post-wrapper">
<div>
<img src="/assets/img/laying.png">

Technology is a tool. Unfortunately, we don’t always utilize it properly. With the way the internet 2.0 is designed, it’s easy to waste your precious time mindlessly scrolling and tapping. Our aim is to share evidence-based strategies to help you improve your relationship with tech, and stay up to date on how the evolution of technology is shaping society. We want to contribute to a paradigm shift in how people use technology, focusing on awareness, intention, and true social connectivity.
</div>
</div>
<div id="team"><h2>TEAM</h2>
<div class="team-container">
  {% for author in site.authors reversed %}
    <div class="blog-column team">
    {%- include author-details.html -%}
    </div>
  {% endfor %}
</div>
</div>
