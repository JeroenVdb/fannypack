---
title: Pagination
description: Navigate between pages of related content across multiple pages
menus: Modules
---

If you have a lot of content, pagination can be a solution to divide it smaller portions.

<div class="fp-example">
	<nav class="pagination" role="navigation" aria-label="Pagination">
		<ol class="pagination__list">
			<li class="pagination__item pagination__item--previous" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to previous page, page 1">Previous</a>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to page 1">1</a>
			</li>
			<li class="pagination__item is-active" role="none presentation">
				<span class="pagination__link" aria-label="Current page, page 2" aria-current="true">2</span>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to page 3">3</a>
			</li>
			<li class="pagination__item pagination__item--dummy" role="none presentation">
				<span class="pagination__link" aria-hidden="true">&hellip;</span>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to last page, page 15">15</a>
			</li>
			<li class="pagination__item pagination__item--next" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to next page, page 2">Next</a>
			</li>
		</ol>
	</nav>
</div>

{% highlight html %}
<nav class="pagination" role="navigation" aria-label="Pagination">
	<ol class="pagination__list">
		<li class="pagination__item pagination__item--previous" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Go to previous page, page 1">Previous</a>
		</li>
		<li class="pagination__item" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Go to page 1">1</a>
		</li>
		<li class="pagination__item is-active" role="none presentation">
			<span class="pagination__link" aria-label="Current page, page 2" aria-current="true">2</span>
		</li>
		<li class="pagination__item" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Go to page 3">3</a>
		</li>
		<li class="pagination__item pagination__item--dummy" role="none presentation">
			<span class="pagination__link" aria-hidden="true">&hellip;</span>
		</li>
		<li class="pagination__item" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Go to last page, page 15">15</a>
		</li>
		<li class="pagination__item pagination__item--next" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Go to next page, page 2">Next</a>
		</li>
	</ol>
</nav>
{% endhighlight %}

## Disabled states

You can disable pagination items with `.is-disabled` or `.js-is-disabled`. You also need to change some WAI-ARIA attributes and (optionally) change the tag from `<a>` to `<span>`.

<div class="fp-example">
	<nav class="pagination" role="navigation" aria-label="Pagination">
		<ol class="pagination__list">
			<li class="pagination__item pagination__item--previous is-disabled" role="none presentation">
				<span class="pagination__link" aria-hidden="true">Previous</span>
			</li>
			<li class="pagination__item is-active" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Current page, page 1" aria-current="true">1</a>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to page 2">2</a>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to page 3">3</a>
			</li>
			<li class="pagination__item pagination__item--dummy" role="none presentation">
				<span class="pagination__link" aria-hidden="true">&hellip;</span>
			</li>
			<li class="pagination__item" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to last page, page 15">15</a>
			</li>
			<li class="pagination__item pagination__item--next" role="none presentation">
				<a href="#" class="pagination__link" aria-label="Go to next page, page 2">Next</a>
			</li>
		</ol>
	</nav>
</div>

{% highlight html %}
<nav class="pagination" role="navigation" aria-label="Pagination">
	<ol class="pagination__list">
		<li class="pagination__item pagination__item--previous is-disabled" role="none presentation">
			<span class="pagination__link" aria-hidden="true">Previous</span>
		</li>
		<li class="pagination__item is-active" role="none presentation">
			<a href="#" class="pagination__link" aria-label="Current page, page 1" aria-current="true">1</a>
		</li>
		...
	</ol>
</nav>
{% endhighlight %}
