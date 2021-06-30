---
title: Hello WORLD !
author: robert
date: 2013-11-29 00:00:00 +0200
categories: technical
tags: banana fruit
---
A banana is an edible fruit – botanically a berry – produced by several kinds
of large herbaceous flowering plants in the genus Musa.

In some countries, bananas used for cooking may be called "plantains",
distinguishing them from dessert bananas. The fruit is variable in size, color,
and firmness, but is usually elongated and curved, with soft flesh rich in
starch covered with a rind, which may be green, yellow, red, purple, or brown
when ripe.

```html
<!doctype html>
<html>
	<head>
		<meta charset="utf-8">
		<title>{{ page.title }}</title>
		<link rel="stylesheet" href="{{ site.url }}/style.css" />
		<link rel="alternate" type="application/atom+xml" title="{{ site.title }}" href="{{ site.url }}/feed.xml">
	</head>
	<body>
		{% include header.html %}
		<!--<a class="btn btn-rss" href="{{ site.url }}/feed.xml" target="_blank">RSS</a>-->
		<main>
			<div id="content">
				{{ content }}
			</div>
		</main>
	</body>
</html>
```