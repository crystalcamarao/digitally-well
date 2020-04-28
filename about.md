---
title: About
permalink: "/about/"
layout: page
---

<img src="/assets/img/laying.png" height="400px">

Technology is a tool. Unfortunately, we don’t always utilize it properly. With the way the internet 2.0 is designed, it’s easy to waste your precious time mindlessly scrolling and tapping. Our aim is to share evidence-based strategies to help you improve your relationship with tech, and stay up to date on how the evolution of technology is shaping society. We want to contribute to a paradigm shift in how people use technology, focusing on awareness, intention, and true social connectivity.

<h2>TEAM</h2>
<div class="about-container">
{% for author in site.authors %}
<div class="main-home main-home-left"><h3> <a href="{{ author.url }}">{{ author.title }}</a></h3</div>
{% endfor %}

</div>