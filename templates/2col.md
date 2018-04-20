---
title: Two col
description: A two column layout, 1 column for the content and a sidebar for complementary content.
modifier: layout--fixed-header
menus: Templates
---

<div class="grid">
	<div class="col-8">
		<article class="article">
			<h1>2 col template</h1>
			<p>1 column for the main content and a sidebar for some complementary content about the main content. </p>
		</article>
	</div>
	<div class="col-4">
		<aside role="complementary">
			<h2>Sidebar</h2>
			<p>Here some complementary info about the main article.</p>
		</aside>
	</div>
</div>


{% highlight html %}
<!DOCTYPE html>
<html lang="en" class="no-js">
<head>...</head>
<body>
	<header class="site-header">...</header>
	<main class="main-container" role="main">
		<div class="main-content">
			<div class="container">
				<div class="grid">
					<div class="col-8">
						<!-- or any other .col-X -->
					</div>
					<div class="col-6">
						<!-- or any other .col-X -->
					</div>
				</div>
			</div>
		</div>
	</main>
</body>
</html>
{% endhighlight %}



