---
layout: default
title: Home
---


<header>
	<div class="headerleft"><img src='logo.svg'></div>
	<div class="headerright"><p>TEXTTTTTTTTTTTTTTTTT</p></div>
</header>
<div class="posts">

	

  {% for post in site.posts %}
    <h1>
       {{ post.date | date: "%F %j"}}
    </h1>
  {% endfor %}


</div>