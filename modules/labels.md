---
title: Labels
description: Giving a visual representation to small pieces of content
menus: Modules
---

## a11y ready

The coloring of the label text is done by comparing contrast of a given color in the [YIQ color space](https://en.wikipedia.org/wiki/YIQ) to the light/dark arguments and returns whichever is most "contrasty"

<div class="fp-example">
	<span class="label">default</span>
	<span class="label label--success">success</span>
	<span class="label label--warning">warning</span>
	<span class="label label--error">error</span>
	<span class="label label--primary">primary</span>
	<span class="label label--secondary">secondary</span>
</div>

{% highlight html %}
<span class="label">default</span>
<span class="label label--success">success</span>
<span class="label label--warning">warning</span>
<span class="label label--error">error</span>
<span class="label label--primary">primary</span>
<span class="label label--secondary">secondary</span>
{% endhighlight %}

## Outline style

<div class="fp-example">
	<span class="label label--outline">default</span>
	<span class="label label--success label--outline">success</span>
	<span class="label label--warning label--outline">warning</span>
	<span class="label label--error label--outline">error</span>
	<span class="label label--primary label--outline">primary</span>
	<span class="label label--secondary label--outline">secondary</span>
</div>

{% highlight html %}
<span class="label label--outline">default</span>
<span class="label label--success label--outline">success</span>
<span class="label label--warning label--outline">warning</span>
<span class="label label--error label--outline">error</span>
<span class="label label--primary label--outline">primary</span>
<span class="label label--secondary label--outline">secondary</span>
{% endhighlight %}

## Links

Using the `.label` classes with the `<a>` element quickly provide *actionable* badges with hover and focus states.

<div class="fp-example">
	<div>
		<a href="#" class="label">default</a>
		<a href="#" class="label label--success">success</a>
		<a href="#" class="label label--warning">warning</a>
		<a href="#" class="label label--error">error</a>
	</div>
	<div style="margin-top: 10px;">
		<a href="#" class="label label--outline">default</a>
		<a href="#" class="label label--success label--outline">success</a>
		<a href="#" class="label label--warning label--outline">warning</a>
		<a href="#" class="label label--error label--outline">error</a>
	</div>
</div>

{% highlight html %}
<a href="#" class="label">default</a>
<a href="#" class="label label--success">success</a>
<a href="#" class="label label--warning">warning</a>
<a href="#" class="label label--error">error</a>

<a href="#" class="label label--outline">default</a>
<a href="#" class="label label--success label--outline">success</a>
<a href="#" class="label label--warning label--outline">warning</a>
<a href="#" class="label label--error label--outline">error</a>
{% endhighlight %}

## More colours

<div class="fp-example">
	<div>
		<a href="#" class="label label--coolblue">cool blue</a>
		<a href="#" class="label label--duskblue">dusk blue</a>
		<a href="#" class="label label--lightbluegrey">light blue grey</a>
		<a href="#" class="label label--slate">slate</a>
		<a href="#" class="label label--dark">dark</a>
		<a href="#" class="label label--warmgrey">warm grey</a>
	</div>
	<div style="margin-top: 10px;">
		<a href="#" class="label label--lightishpurple">lightish purple</a>
		<a href="#" class="label label--cornflower">cornflower</a>
		<a href="#" class="label label--lightteal">light teal</a>
		<a href="#" class="label label--sunyellow">sun yellow</a>
		<a href="#" class="label label--apricot">apricot</a>
		<a href="#" class="label label--lightsalmon">light salmon</a>
	</div>
	<div style="margin-top: 10px;">
		<a href="#" class="label label--facebook">facebook</a>
		<a href="#" class="label label--twitter">twitter</a>
		<a href="#" class="label label--instagram">instagram</a>
		<a href="#" class="label label--youtube">youtube</a>
		<a href="#" class="label label--spotify">spotify</a>
		<a href="#" class="label label--soundcloud">soundcloud</a>
	</div>
</div>

{% highlight html %}
<span class="label label--coolblue">cool blue</span>
<span class="label label--duskblue">dusk blue</span>
<span class="label label--lightbluegrey">light blue grey</span>
<span class="label label--slate">slate</span>
<span class="label label--dark">dark</span>
<span class="label label--warmgrey">warm grey</span>

<span class="label label--lightishpurple">lightish purple</span>
<span class="label label--cornflower">cornflower</span>
<span class="label label--lightteal">light teal</span>
<span class="label label--sunyellow">sun yellow</span>
<span class="label label--apricot">apricot</span>
<span class="label label--lightsalmon">light salmon</span>

<span class="label label--facebook">facebook</span>
<span class="label label--twitter">twitter</span>
<span class="label label--instagram">instagram</span>
<span class="label label--youtube">youtube</span>
<span class="label label--spotify">spotify</span>
<span class="label label--soundcloud">soundcloud</span>
{% endhighlight %}
