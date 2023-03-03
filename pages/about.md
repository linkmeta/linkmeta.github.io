---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**
{% include elements/highlight.html text="I am highlighted text." %}
> Hi I am **{{ site.author.name }}** :wave:,<br>
> Location: ShangHai.<br>
> Email: qqnokia@gmail.com | qqnokia@msn.com.<br>
> Link to the meta world.<br>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>