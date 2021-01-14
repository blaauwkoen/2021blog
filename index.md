---
layout: default
title: Home
---
<h1>{{ "Hello World!" | downcase }}</h1>

<div class="posts">

	<ul>

  {% for post in site.posts %}
    <li>
      {{ post.title }}
    </li>
  {% endfor %}
</ul>

</div>