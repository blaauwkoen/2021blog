---
layout: default
title: Home
---
<h1>{{ "Hello World!" | downcase }}</h1>

<div class="posts">

	<ul>

  {% for post in site.posts %}
    <h1>
       {{ post.date | date: "%F %j"}}
    </h1>
  {% endfor %}
</ul>

</div>