---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About me**
4+ years of hands on web development. Self driven, dedicated and problem solving software engineering professional.
Passionate and creative about Object Oriented Programming software development.<br>
Looking for <b>remote contracts or full-time positions</b>

# **Resume / CV**
<a href="{{ site.author.resume }}.pdf">PDF</a> or <a href="{{ site.author.resume }}.docx">DOCX</a>?

# **Skills**
<div class="row">
{% include about/skills.html title="Java" source=site.data.technical-skills %}
{% include about/skills.html title=".NET" source=site.data.languages %}
{% include about/skills.html title="JavaScript" source=site.data.languages %}
</div>
<div class="row">
{% include about/skills.html title="Management skils" source=site.data.management-skills %}
{% include about/skills.html title="Team skills" source=site.data.team-skills %}
</div>
<div class="row">
{% include about/skills.html title="Languages fluency" source=site.data.languages %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>