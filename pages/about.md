---
layout: page
title: About
permalink: /about/
weight: 3
---

# **Consulting**
Hi, I'm <b>{{site.author.name}}</b>, the CEO of a consulting company called <b>Maris</b>. We are customer focused and a hands on consultancy company based in Europe. Hit me up for details if you need competent and flexible developer for your project

# **About me**
4+ years of hands on web development. Self driven, dedicated and problem solving software engineering professional. Passionate and creative about Object Oriented Programming software development. Looking for remote contracts or full-time positions.

# **Resume / CV**
<a href="{{ site.author.resume }}">Here!</a>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>