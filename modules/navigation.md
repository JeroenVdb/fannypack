---
title: Navigation
description: Main navigation component
menus: Modules
---

Standard horizontal navigation. Mostly used in the heading.

<div class="fp-example">
	<nav class="nav" role="navigation" aria-label="Primary navigation">
		<ul class="nav__list">
			<li class="nav__item" role="none">
				<a href="#" class="nav__link">Home</a>
			</li>
			<li class="nav__item" role="none">
				<a href="#" class="nav__link">Products</a>
			</li>
			<li class="nav__item is-active" role="none">
				<a href="#" class="nav__link" aria-current="page">About</a>
			</li>
		</ul>
	</nav>
</div>

{% highlight html %}
<nav class="nav" role="navigation" aria-label="Primary navigation">
	<ul class="nav__list">
		<li class="nav__item" role="none">
			<a href="#" class="nav__link">Home</a>
		</li>
		<li class="nav__item" role="none">
			<a href="#" class="nav__link">Products</a>
		</li>
		<li class="nav__item is-active" role="none">
			<a href="#" class="nav__link" aria-current="page">About</a>
		</li>
	</ul>
</nav>
{% endhighlight %}

<table class="table table--horizontal-borders">
	<thead>
		<tr>
			<th>Selector</th>
			<th></th>
			<th>Description</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><code>role="navigation"</code></td>
			<td><span class="label label--warning">Required</span></td>
			<td>For a11y</td>
		</tr>
		<tr>
			<td><code>aria-label="Primary navigation"</code></td>
			<td><span class="label label--warning">Required</span></td>
			<td>To make a distinction with the <code>&lt;nav&gt;</code> used in <a href="{% link modules/breadcrumb.md %}">breadcrumbs</a> or <a href="{% link modules/pagination.md %}">pagination</a>. Translate this string to your current locale.</td>
		</tr>
		<tr>
			<td><code>aria-current="page"</code></td>
			<td><span class="label label--warning">Required</span></td>
			<td>Only required if one of the links matches the current page.</td>
		</tr>
	</tbody>
</table>

## Vertically stacked

<div class="fp-example">
	<nav class="nav nav--vertical" role="navigation" aria-label="Primary navigation">
		<ul class="nav__list">
			<li class="nav__item" role="none">
				<a href="#" class="nav__link">Home</a>
			</li>
			<li class="nav__item" role="none">
				<a href="#" class="nav__link">Products</a>
			</li>
			<li class="nav__item is-active" role="none">
				<a href="#" class="nav__link" aria-current="page">About</a>
			</li>
		</ul>
	</nav>
</div>

{% highlight html %}
<nav class="nav nav--vertical" role="navigation" aria-label="Primary navigation">
	<ul class="nav__list">
		<li class="nav__item" role="none">
			<a href="#" class="nav__link">Home</a>
		</li>
		<li class="nav__item" role="none">
			<a href="#" class="nav__link">Products</a>
		</li>
		<li class="nav__item is-active" role="none">
			<a href="#" class="nav__link" aria-current="page">About</a>
		</li>
	</ul>
</nav>
{% endhighlight %}
