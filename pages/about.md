---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About me**
8 years of hands on web development. Self driven, dedicated and problem solving software engineering professional.
Passionate and creative about Object Oriented Programming software development.<br>

# **Resume / CV**
<a href="{{ site.author.resume }}.pdf">PDF</a> or <a href="{{ site.author.resume }}.odt">ODT</a>?

# **Skills**
<div class="row">
{% include about/skills.html title="Java" source=site.data.java-skills %}
{% include about/skills.html title="Front end" source=site.data.javascript-skills %}
</div>
<div class="row">
{% include about/skills.html title="Cloud" source=site.data.cloud-skills %}
{% include about/skills.html title="Database" source=site.data.db-skills %}
</div>
<div class="row">
{% include about/skills.html title="Software Architecture" source=site.data.architecture-skills %}
{% include about/skills.html title="DevOps" source=site.data.devops-skills %}
</div>
<div class="row">
{% include about/skills.html title="Management skills" source=site.data.management-skills %}
{% include about/skills.html title="Team skills" source=site.data.team-skills %}
</div>

# **Experience**
<div class="row">
{% include about/timeline.html %}
</div>