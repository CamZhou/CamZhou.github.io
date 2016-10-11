---
layout: home
title: Home
landing-title: Hi, my name is Cam
description: 
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Get Started</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Cam Zhou</h2>
		</header>
		<p>Cam Zhou is a CS major at Harvey Mudd College. Besides the Computer Science background, he also enjoys taking pictures.</p>
		<ul class="actions">
			<li><a href="landing.html" class="button next">View More Pictures</a></li>
		</ul>
	</div>
</section>

</div>

